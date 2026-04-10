# CustomerSegmentation_dataAnalysis
Pattern Mining Analysis: Retail Customer Segmentation Dataset

Abstract
This notebook applies the Apriori algorithm and association rule mining to a retail customer segmentation dataset of 50,000 customers with 14 behavioral and demographic attributes. All continuous variables are discretized into domain-aware categorical bins, transforming each customer profile into a transaction. The Apriori algorithm (min_support=0.10) extracts 472 frequent itemsets, from which 86 association rules are generated (min_confidence=0.55, min_lift=1.0). Closed and maximal frequent itemsets are also computed. Three unique patterns are uncovered: two perfect-confidence deterministic rules linking spend, frequency, and order value; a behavioral fingerprint identifying Occasional customers as high-AOV low-frequency shoppers; and a counter-intuitive discovery that Loyal customers are habitual micro-buyers, not high-value spenders.
