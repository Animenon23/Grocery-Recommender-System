# Grocery Products Recommender System

Business Use Case:
Customers make online grocery purchases from the Instacart grocery delivery service.
When a customer buys an item, what are the related or complementary items that can be presented to them to promote cross-selling?
How can we mine association rules between various grocery items?

Data Methodology:
The project started by preprocessing the dataset and creating a one-hot encoded representation of the transactions. The Apriori algorithm was then applied to identify frequent itemsets, using a minimum support threshold. Subsequently, association rules were generated from the frequent itemsets, considering a minimum confidence threshold. Evaluation of the rules was based on metrics such as support, confidence, and lift, which provided insights into the strength and significance of the relationships.


Follow the PDF for step by step approach and data sources.
