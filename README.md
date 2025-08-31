#  Business Case: Aerofit - Descriptive Statistics & Probability

#  About Aerofit

Aerofit is a leading brand in the field of fitness equipment. Aerofit provides a product range including machines such as treadmills, exercise bikes, gym equipment, and fitness accessories to cater to the needs of all categories of people.

#  Business Problem

The market research team at AeroFit wants to identify the characteristics of the target audience for each type of treadmill offered by the company, to provide a better recommendation of the treadmills to the new customers. The team decides to investigate whether there are differences across the product with respect to customer characteristics.

Perform descriptive analytics to create a customer profile for each AeroFit treadmill product by developing appropriate tables and charts.
For each AeroFit treadmill product, construct two-way contingency tables and compute all conditional and marginal probabilities along with their insights/impact on the business.

# Tools used

*  Python
*  Pandas, Matplotlib, Seaborn

# Project Type

Basic EDA and Probability 

#  Dataset 
Dataset link: [Aerofit_treadmill.csv](https://d2beiqkhq929f0.cloudfront.net/public_assets/assets/000/001/125/original/aerofit_treadmill.csv?1639992749)

# Columns

| Column Name        | Description                                                                 |
|-------------------|-----------------------------------------------------------------------------|
| Product Purchased  | KP281, KP481, or KP781                                                      |
| Age                | In years                                                                    |
| Gender             | Male/Female                                                                 |
| Education          | In years                                                                    |
| MaritalStatus      | Single or Partnered                                                         |
| Usage              | Average number of times the customer plans to use the treadmill each week   |
| Income             | Annual income (in $)                                                        |
| Fitness            | Self-rated fitness on a 1-to-5 scale (1 = poor, 5 = excellent)             |
| Miles              | Average number of miles the customer expects to walk/run each week     

#  Product Portfolio:

The KP281 is an entry-level treadmill that sells for $1,500.
The KP481 is for mid-level runners that sell for $1,750.
The KP781 treadmill is having advanced features that sell for $2,500.

# Solution Approach

1. Data Collection
2. Understood Business Problem
3. Basic EDA
4. Probability using Contigency table
5. Customer profiling
6. Derived insights and actionable recommendations

# Recommendations

*  Based on the analysis, age is not a significant factor, so Aerofit can continue focusing on all age groups for all three products.

*  Customers with low to medium income prefer both KP281 and KP481. Therefore, Aerofit should continue focussing on customers with an income less than $60000 customers across all gender and maritalstatus.

*  Aerofit has higher number of customers for KP281 and KP481 in the low-income group, compared to the high-income users of KP781. Therefore, Aerofit should focus on targeting the high income group including both male and female customers through customized marketing campaigns, Brand ambassador programs, and premium promotions that highlight the KP781's exclusive features aiming to increase its sales among this segment.

*  KP281 makes up 44.44% of purchases, which is double that of KP781 (22.22%). There fore Aerofit should consider reducing the price of KP281 even slightly. This strategy could help capture even more customers, particularly in the low income group.

*  Since the probability of female customers buying KP781 is only 9.2%, Aerofit should conduct a survey with existing female customers to understand why they prefer other products over KP781. This feedback will help identify areas for improvement and suggest ways to better meet female customers needs.
