# Problem statement:
This project is based on social media link prediction whether two users are going to be friend in future or not. 
# Data Overview
data from facebook's recruting challenge on kaggle https://www.kaggle.com/c/FacebookRecruiting data contains two columns source and destination eac edge in graph
1.Data columns (total 2 columns):
    source_node int64, destination_node int64

# Business objectives and constraints:
No low-latency requirement. Probability of prediction is useful to recommend ighest probability links.
# Performance metric for supervised learning:
Both precision and recall is important so F1 score is good choice Confusion matrix. 
