# Maximize-Revenue-for-Taxi-Drivers

# Maximizing Revenue for Taxi Cab Drivers through Payment Type Analysis

# Problem Statement
In the fast-paced taxi booking sector, making the most of revenue is essential for long-term success and driver happiness. 
Our goal is to use data-driven insights to maximise revenue streams for taxi drivers in order to meet this need. Our research 
aims to determine whether payment methods have an impact on fare pricing by focusing on the relationship between payment type
and fare amount.

# Objective
This project main goal is to run A/B test to examine the relationship between the total fare and the method of payment.
We use Python hypothesis testing and descriptive statistics to extract useful information that can help taxi drivers generate 
more cash.in particular, we want to find out if there is big difference in the fares for those who pay with credit card vs
those who pay with cash.

# Data Summary
tpep_pickup_datetime:- The date and time when the meter was engaged.

tpep_dropoff_datetime	:-  The date and time when the meter was disengaged.

passenger_count:- The number of passenger in the vehicle.

trip_distance:- The elapsed trip distance in mles repoorted by the taximeter.

payment_type:- A numeric code signifying how the passenger paid for the trip. 1= Credit card, 2= Cash

fare_amount:- The time and distance fare calculated by the meter.

trip_duration: The elapsed trip duration in minutes calculate by me.

# EDA 
## 1) Preference of Payment Type

   :- The proportion of customers paying with cards is significantly higher than those paying with cash, with card payments    accounting for 64% of all 
      transactions compared to cash payments at 34%. 

   :- This indicates a strong preference among customers for using card payments over cash potentially due to convenience, security,or incentives offered for card 
      transactions.

## 2) Payment Distribution by Type
      
   :- Among card payments,rides with single passenger (No. of Passenger=1) comprise the largest propotion,
      constituting 40% of all card transactions.

   :- Similarly,cash payments are predominantly associated with single passenger rides,making up 23% of all cash transactions.

   :- There is a noticeable decrease in the percentage of transactions as the passenger count increases.    

# Hypothsis Testing (T-test)

Null Hypothesis :- There is no difference in average fare between customers who use credit cards and customer who use cash.
    
Alternate Hypothesis :- There is a difference in average fare between customers who use credit cards and customer who use cash.

# Conclusion

:- We are rejecting null hypothesis.so we accept the alternate hypotheisis. 
    
:- Alternate Hypothesis :- There is a difference in average fare between customers who use credit cards and customer who use cash.  

:- with T-statistics: 30.99 and p-value of less than 0.05, we reject the null hypothesis, suggesting that there is indeed a significant difference in average fare between the two payment methods.

# Recommendations

:-  Encourage customers to pay with credit cards to capitalize on the potential for generating more revenue for taxi cab drivers.
    
:-  Implement strategies such as offering incentives or discounts for credit card transactions to incentivize customers to choose this payment method.
    
:-  Provide seamless and secure credit card payment options to enhance customer convenience and encouuragebadoption of this preferred payment method.    
