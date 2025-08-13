# Will-the-Customer-Accept-the-Coupon
Assignment 5 solution

#### Jupyter N/B Link: https://github.com/Ankurgarg1232/Will-the-Customer-Accept-the-Coupon



## Goal

To answer the question: “Will a customer accept the coupon?” 
Use visualizations and probability distributions to distinguish between customers who accepted a coupon versus those who did not.


## Data

This data comes to us from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios including the destination, current time, weather, passenger, etc., and then ask the person whether he will accept the coupon if he is the driver. Answers that the user will drive there ‘right away’ or ‘later before the coupon expires’ are labeled as ‘Y = 1’ and answers ‘no, I do not want the coupon’ are labeled as ‘Y = 0’.  There are five different types of coupons -- less expensive restaurants (under \$20), coffee houses, carry out & take away, bar, and more expensive restaurants (\$20 - $50).

## Exploratory Data Analysis


First step was to load the data and check for null values, there were so many nulls value in car column, so just replaced them with a string, and dropped for other columns, as they were very few in number compared to the total dataset.
Appropriate values were selected from columns according to the problem and most of the preprocessing steps were verified. Important Visualizations are available in the Notebook. 

## Findings
After analysing the data, it seems like the coupon acceptance rate is higher among the people with following characteristics: 


- **Frequent Bar visiters** and are **older than 25 years**.
- **Singles** are more likey to the accept the coupons.
- People who **frequently visits cheap Restaurants** are more likely to accept.
- Drivers having **Kid(s) with them have lower acceptance chances**, etc. 
- Who **aren't Widowed**.
- **Doesn't work for occupation like Farming, Forestory, etc**.


## Recommendations

- It is recommended to give Bar Coupons people among age b/w 25-30 years.
- Singles, or people driving alone.
- Give coupons to places, which takes less time for people to reach the venue.
- Carry out coupons are more likey to get accepted, so give them more.

