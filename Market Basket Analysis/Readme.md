#Market Basket Analysis

Market Basket refers to a selection of goods and services that are consistently purchased and sold throughout an economic system. it is a data mining technique that is used by retailers to analyze the purchase behaviour of customers. This tecniques helps to identifies the relationship between different products and how they are purchased together.

Market Basket Analysis is a dataset from a groceries store that consists of 3 columns namely; Member_numebr, Data and Item_description.

Exploratory data analysis was carried out on the dataset, and there were 167 unique items, data was converted to date format for easy analysis. The data was from 2014-2015, there was an increase in sales in the year 2015 and where August recorded the highest sales.

Whole milk was the most sold item whole Kitchen utensils and preservation [roducts were the least sold item.

I used Apriori algorithms for the MBA, to identify association rules among items and to find item sets that are frequently bought together. Support, Confidence and Lift values of the association rules to understand the strength and significance of the relationship.

Points on the scatter plot represent individual association rules. Larger points (markers) indicate higher lift values, meaning stronger associations. Points positioned toward the upper-right part of the plot indicate rules with both high support and high confidence. Rule 24 and Rule 25:Antecedents:(whole milk), Consequents:(yogurt) has the highest Lift value of 1.16,People who buy whole milk are 32.87% likely to buy yogurt and People who buy yogurt are 53.22% likely to buy whole milk. This means when they are placed together sales will potentially increase.

