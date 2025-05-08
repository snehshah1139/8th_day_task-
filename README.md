# 8th_day_task-
# Task 8: Clustering with K-Means

# Objective  
Segment mall customers into meaningful groups using unsupervised learning (K-Means Clustering).

# Tools Used  
Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

# Dataset Overview

| Column | Description |
|--------|-------------|
| CustomerID | Unique ID of each customer |
| Gender | Male or Female |
| Age | Customer's age |
| Annual Income (k$) | Annual income in thousands |
| Spending Score (1-100) | Score based on customer behavior |

# EDA Summary  
- Balanced gender distribution  
- No direct correlation between income and spending  
- Young customers show diverse spending behaviors

# Preprocessing  
- Selected numerical features: Age, Income, Spending Score  
- Standardized data for clustering

# Elbow Method  
- Optimal number of clusters (K) = 5 based on elbow point

# K-Means Clustering  
- Applied K-Means with K=5  
- Assigned cluster labels to each customer

# Evaluation  
- Silhouette Score: 0.554  
- Indicates well-defined, meaningful clusters

# Cluster Summary  
- Cluster 0: Middle-aged, average income, moderate spending  
- Cluster 1: Young, high income, high spending  
- Cluster 2: Young, low income, high spending  
- Cluster 3: Older, high income, low spending  
- Cluster 4: Older, low income, low spending

# Conclusion  
K-Means successfully grouped customers into 5 useful segments to support targeted marketing and business decisions.

