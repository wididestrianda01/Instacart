# Instacart Customer Segmentation and Market Basket Analysis

**Instacart** is an American company that operates a grocery delivery and pick-up service in the United States and Canada. The company offers its services via a website and mobile app. The service allows customers to order groceries from participating retailers with the shopping being done by a personal shopper.

With the large customer base, the company collects data of the users’ transactions behaviour and purchasing history. 

**The objective** of this study is to increase profitability by tailoring suitable marketing approach and find key driver to used as a lever to improve profit.

The dataset contains a sample of over 3 million grocery orders from more than 200,000 Instacart users.

Data originally comes from https://www.instacart.com/datasets/grocery-shopping-2017

My data:  https://www.kaggle.com/c/instacart-market-basket-analysis

Business Implication resulting from this study can be found in the pdf file.

## Methodology
From the research question `How to find lever from customer transaction behaviour and purchasing history to improve profitability?`

Customer Segmentation based on Spending Profile is used to generate tailored marketing approach
Customer Segmentation based on Buying Pattern is used as input to Association Rule Algorithm

Market Basket Analysis is conducted to determine key driver to increase profit

### Customer Segmentation based on Spending Profile

By using RFM Model
RFM (recency, frequency and monetary) model is a behavior-based model used to analyze the behavior of a customer by measuring when people buy, how often they buy and how much they buy. Segmentation is obtained using K-Means Clustering.


### Customer Segmentation based on Buying Pattern
By combining clustering & association rules, the information obtained will be more detailed, and avoid the possibility of rules that are not caught or overshadowed by other rules because they are a minority. Maybe there are association rules that is common for certain groups of people, but not for majority of people.

### Market Basket Analysis
Market Basket Analysis is conducted using the buying pattern clsuter.
Association rule is performed using 3 algorithm: apriori, FP-Growth, and ECLAT.

## Conclusion
* There are 4 Cluster Customer
  * Loyal Customer
  * Hibernating
  * Big Spender
  * Promising

* There are 251 assocation rules generated from customer buying pattern.
