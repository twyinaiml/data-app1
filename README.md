
# Data Science Pratical Application: 
# Will the Customer Accept the Coupon?

# Data:
This data comes to us from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios, including the destination, current time, weather, passenger, etc., and then asks people whether they will accept the coupon if they are the driver. Answers given that the users will drive there “right away” or “later before the coupon expires” are labeled as “Y = 1”, and answers “no, I do not want the coupon” are labeled as “Y = 0”. 

# Data Cleanup
This dataset has 26 columns but there are 13370 missing values in 6 columns. I also found there is a typo in a column. We have to fix all these issues before starting data analytics.

# Data Analytics
There are five different types of coupons: less expensive restaurants (under $20), coffee houses, carry out and take away, bars, and more expensive restaurants ($20–$50). By applying pandas statistics library, we get the following coupon acceptance ratio values:
- mean = 0.56
- std = 0.15
- min = 0.41
- max = 0.73

# Findings
- This dataset contains 12684 rows and 26 columns
- The average coupon accepted rate is 56.8% (7210 out of 12684)
- Take out coupons has the highest accepted rate 73.5%
- One-day coupons have a higer acceptance rate than 2-hour coupons
- Low-cost restaurant coupons has a higher acceptance rate than expensive restaurants
- 

# Summary
In general, the average coupon acceptance ratio is low while customers are driving in different scenarios. However, we see coupon acceptance ratio increases to more than 70% when we target a special group of customers. For instance, customers who visited bars more often and age under 30 have a higher ratio to accept bar coupons. This indicates that we should associate coupon types with customer shopping bahaviors and their characteristics in order to improve acceptance ratio.
