# Business Insights
Income has been the consistent variable across all the models built. This shows that it the most important variable to consider.

From the tree report the final model, we see the following segments/variable combinations of customers who have a strong probability of borrowing loans.

Higher Income and Higher Credit Card Average

Higher Education levels (2 &3) and Higher Income

Larger Family size and high income

Customers with a CDAccount

These potential customer segments can be targeted by the marketing team to increase the conversion rate.

# Possible recommendations to the campaign and business:
A customer with higher income has a better rate of paying back the loans, hence customers should be treated with more incentives in the campaign.

Target customers with high education levels as we see that such customer tend to have high income paying jobs.

Customers with high credit card average are also potential target. Hence the bank can offer suitable combination offers to the banks credit card along with purchasing a loan.
These decision require careful consideration of the bank's lending policies.

Offering Customers with a larger family and high income flow, incentives beneficial to the whole family rather than just the customer.

Almost 50% of customers who have a CD account purchased a loan. Any material from the previous campaign that centered on this area can be improved to increase conversion rate.
The bank may offer lower interest rates at larger payment periods with possible financial investment suggestions to improve customer retention.

A key idea would be to help educate/provide insights to the customers on better money management, saving and refinancing solutions. By ensuring the customer engagement,
the bank can increase its loyalty with its customers.

The Bank and its marketing campaign must ensure that they are updated on all the current social and economic conditions of the market while promoting.

# Recommendations
In this dataset, only 9.6% of total customers purchased a loan after the last campaign.
Although we were able to build a 97% accuracy model with a high recall, the imbalance in the data is very high.
We do not know how the model would predict if the imbalance were to be corrected.


Another imbalance in feature was on Mortgage. More than 50% of customers in this dataset did not have a house/mortgage. 
Even though we saw that mortgage had a positive correlation with Income and customers with higher mortgages also purchased loans, there was heavy skewness in this variable.

We do not know if the lack of significance for Mortgage in our bestmodel2 is due to its skewness or due to no values. 
Since Mortgage is also a type of loan, a better approach would be to separate customers at various mortgage levels and then build a predicting model.

This approach may also bring the location / ZIPCode variable into consideration as Mortgage levels are related to the location of the house.
Certain variables(i.e Online, Securities Account and CreditCard) in the dataset had no significance to the dependent variable. 
Future data collected can ignore these variables and focus more on correcting the imbalance.
