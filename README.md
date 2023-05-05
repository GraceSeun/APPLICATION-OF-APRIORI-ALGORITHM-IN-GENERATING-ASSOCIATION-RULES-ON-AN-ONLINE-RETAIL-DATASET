APPLICATION OF APRIORI ALGORITHM IN GENERATING ASSOCIATION RULES ON AN ONLINE RETAIL DATASET

Association is the relationship between two or more objects. Association rule just like the name is the rule that aids in the identification of a relationship between a set of objects and an object that is already known. Association rule mining is a machine learning technique that helps in identifying associations, correlations, patterns, or dependencies between the variables in a dataset. It is establishing a set of rules that allows us to predict an occurrence based on other occurrences in a set of transactions. It is a machine learning technique that is suitable for numeric, non-numeric and categorical data.

An association rule is made up of two parts. The antecedent (if) and then a consequent (then). If we get the antecedent, then we will also get the consequent. So, the rule is gotten by analysing a data and looking for frequent if-then occurrences.
The measures used in Association Rule Mining are Support, Confidence and Lift.
Support is the total number of transactions containing an item divided by the total number of transactions.
𝑆𝑢𝑝𝑝𝑜𝑟𝑡(𝑥) = 𝑁𝑢𝑚𝑏𝑒𝑟 𝑜𝑓 𝑡𝑟𝑎𝑛𝑠𝑎𝑐𝑡𝑖𝑜𝑛 𝑐𝑜𝑛𝑡𝑎𝑖𝑛𝑖𝑛𝑔 𝑥 / 𝑇𝑜𝑡𝑎𝑙 𝑁𝑢𝑚𝑏𝑒𝑟 𝑜𝑓 𝑡𝑟𝑎𝑛𝑠𝑎𝑐𝑡𝑖𝑜𝑛
Confidence is simply how often the if/then relationship was found to be valid.
𝐶𝑜𝑛𝑓𝑖𝑑𝑒𝑛𝑐𝑒(𝑥 → 𝑦) = 𝑠𝑢𝑝𝑝𝑜𝑟𝑡(𝑥 ∪ 𝑦) / 𝑠𝑢𝑝𝑝𝑜𝑟𝑡(𝑥)
Lift measures the dependence between an if/then item
𝐿𝑖𝑓𝑡(𝑥 → 𝑦) = 𝑐𝑜𝑛𝑓𝑖𝑑𝑒𝑛𝑐𝑒(𝑥 → 𝑦) / 𝑠𝑢𝑝𝑝𝑜𝑟𝑡(𝑦)

Association rule mining is applied in different sectors like the medical field (diagnosis of illness), retail (knowing what goods customers are likely to buy together could play a vital role in the layout of a shop), banking sector (segmentation of clients), and many more.

In this project, association rule mining is used on a dataset which contains transactional information. What items are largely purchased? What group of items are likely to be purchased together? These are some of the questions that would be answered. Apriori algorithm is used to generate association rules. The aim is to get an understanding of association rules, how it works using the transactional dataset for our study and perform data mining on our chosen dataset.
