You have recently been brought on as a data analyst for BankGuard, a financial services company that has been facing a troubling issue: an increasing number of customers are leaving their credit card services. The bank’s management is concerned, as customer churn has a direct impact on revenue and customer loyalty. The Customer Retention Manager has reached out to you with an urgent request: Help us predict which customers are likely to churn so we can take proactive steps to retain them.

They believe that if they can identify customers at risk of leaving, they can offer personalized incentives, improve services, or address customer concerns before it’s too late.

Data description:

Client - number - Unique identifier for the customer holding the account

Attrition_FlagInternal - event (customer activity) variable - if the account is closed then 1 else 0

Customer_AgeDemographic - variable - Customer's Age in Years

GenderDemographic - variable - M=Male, F=Female

Dependent_count - Demographic variable - Number of dependents

Education_Level - Demographic variable - Educational Qualification of the account holder (example: high school, college graduate, etc.)

Marital_Status - Demographic variable - Married, Single, Divorced, Unknown

Income_Category - Demographic variable - Annual Income Category of the account holder (< $40K, $40K - 60K, $60K - $80K, $80K-$120K, > $120K, Unknown)

Card_Category - Product Variable - Type of Card (Blue, Silver, Gold, Platinum)

Monthsonbook - Period of relationship with bank

TotalRelationshipCount - Total no. of products held by the customer

MonthsInactive12_mon - No. of months inactive in the last 12 months

ContactsCount12_mon - No. of Contacts in the last 12 months

Credit_Limit - Credit Limit on the Credit Card

TotalRevolvingBal - Total Revolving Balance on the Credit Card

AvgOpenTo_Buy - Open to Buy Credit Line (Average of last 12 months)

TotalAmtChngQ4Q1 - Change in Transaction Amount (Q4 over Q1)

TotalTransAmt - Total Transaction Amount (Last 12 months)

TotalTransCt - Total Transaction Count (Last 12 months)

TotalCtChngQ4Q1 - Change in Transaction Count (Q4 over Q1)

AvgUtilizationRatio - Average Card Utilization Ratio

NaiveBayesClassifierAttritionFlagCardCategoryContactsCount12monDependentcountEducationLevelMonthsInactive12mon_1 - Naive Bayes

NaiveBayesClassifierA
