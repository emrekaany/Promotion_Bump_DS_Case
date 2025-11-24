Promotion Bump Assignment:
Write a code in R,Python, SAS, Matlab, or software of your choice to do the following.
Attached is the sample data for sales of a company from 2015-01-01 to 2015-08-01. We have gathered information about sales of sample items along with promotion schedule during 2015.
Our goal is to measure the effects of promotion on sales and give recommendations to marketing department for future promotion campaigns.
Data = Assignment4.1a.csv
The data contains daily sales of sample of items in several stores on a specific time frame.
Negative sale quantities represents returns. Each row represents a sale (or return) activity for an item in a store at a specific day. If a store-item combination has no observation in a certain day you can assume there is no sales for that item at that store at that day
Data=Promotiondates.csv
The data contains beginning and the end dates of 6 promotions that took place in 2015.


Your goal is to model the effect of promotion on products and stores. At this stage only use the data in the file Assignment4.1a.csv and base your model using the first 4 promotions.
In order to answer below questions you should divide product and stores into 3 clusters each. Product with higher average weekly sale per store during non-promotion periods will be called “Fast items” and items with lower weekly average sale per store will be labeled as “Slow items”, items in between will be called “Medium items”. Grouping parameters selection is left to you. Apply similar approach to Stores as well.
What are your criteria for separating Fast, Medium and Slow items? Why?
What are your criteria for separating Fast, Medium and Slow Stores? Why?
Which items experienced the biggest sale increase during promotions?
Are there stores that have higher promotion reaction?
What is the biggest effect explaining sales change during promotions?
Is there any significant difference between promotion impacts of the Fast versus Slow items?
Is there any significant difference between promotion impacts of the Fast versus Slow stores?
Data = Assignment4.1b.csv
The data contains daily sale of sample items in several stores after the initial data ends. This will enable you to evaluate your models predictive power on the newly observed data.


B.  You are asked to measure how well your model have worked on this new data. Based on the
model developed in part A forecast what would the effect of promotion 5 will be on sample store – item pairs. Compare your forecasts results for promotion5 with the real observed sales during that period.
What measure would you use for goodness of fit? How good is your model developed in step 1?
What are the main problem points causing bad fits? What would you change in step 1?
Note: You will not be judged on goodness of your fit at step 1.


Report:
Please write a small report covering the points below. You can assume that client`s goal is to understand the reaction of the products and stores during promotions and to measure the effect of promotions on sales in the store. Please include your code at the end of the report. We would like to know how you achieve the conclusion. Which methods did you use?
Make recommendations.
Show your work by providing code.
Report statistics for all models used.
Interpret results.
Is there any data set that you would like to use in addition to tables provided for this assignment? What are those data sets? How would you obtain them?


Bonus
Is there any significant difference in item return rates after promotions?
The assignment4.1c file contains categorical data about the products. ProductGroup1 has a higher hierarchy than ProductGroup2. For example: If ProductGroup1 is 'Top Clothing' then related
ProductGroup2s can be 'T-shirt', 'Shirt' etc. This data can be useful in the analysis and report.
