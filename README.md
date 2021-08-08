# Analysis of Loyalty program

This is an analysis of a mocked up loyalty program, trying to calculate metrics such as Basket Penetration, Revenue penetration and Lift.

## Loyalty Terms learnt 

1. Penetration : The number of customers enrolled in a Loyalty program when compared to the total customers base. Penetration can be calculated in terms of number of baskets or total revenue. 

For Penetration in terms of number of baskets, we need to calculate 
`Baskets purchased by Customers enrolled in Loyalty program/Total Customers`

For Penetration in terms of total revenue, we need to calculate 
`Revenue by Customers enrolled in Loyalty program/Total Revenue`

2. Issuance : Number of loyalty points issued to customers.

## Create a virtual environment to use tfcausalimpact library

Goto the home directory of the project and run the below command
`virtualenv venv`

Then run the below 2 commands : 

`venv\Scripts\activate.bat`

`pip install -r requirements.txt`