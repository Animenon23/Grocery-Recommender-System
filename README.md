# Recommender-System-for-Products

Business Use Case:
Customers make online grocery purchases from the Instacart grocery delivery service.
When a customer buys an item, what are the related or complementary items that can be presented to them to promote cross-selling?
How can we mine association rules between various grocery items?

Data Methodology:
We began by preprocessing the dataset and creating a one-hot encoded representation of the transactions. Using the Apriori algorithm, we identified frequent itemsets based on a minimum support threshold. From the frequent itemsets, we generated association rules considering a minimum confidence threshold. The rules were evaluated based on metrics such as support, confidence, and lift, which provide insights into the strength and significance of the relationships.
