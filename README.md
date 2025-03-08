# E-commerce-app
Overview
The Customer Segmentation App uses K-Means clustering to segment customers based on their transactional behavior and demographics. The app groups customers into meaningful clusters, providing actionable insights to improve marketing strategies and customer retention.

Dataset
The app works with the following CSV files:

customers.csv: Customer information (ID, join date, gender, city).
genders.csv: Gender details (ID, name).
cities.csv: City details (ID, name).
transactions.csv: Coupon transactions (ID, customer, status, coupon name).
branches.csv: Branch details (ID, merchant).
merchants.csv: Merchant information (ID, name).
Workflow
Data Preprocessing: Load, merge, and clean the data from multiple CSV files.
Feature Engineering: Extract features like coupons claimed and burned, then standardize the data.
K-Means Clustering: Segment customers based on their transactional behaviors.
Model Evaluation:
Inertia: Measures how compact the clusters are.
Silhouette Score: Evaluates how well-separated the clusters are.
Visualization:
Elbow method to find optimal k.
Visualize customer distribution across clusters and cluster characteristics.
Recommendations: Provide strategies for targeting each customer segment.
Model Approach
K-Means Clustering
Objective: Group customers based on transactional behavior (coupons claimed, burned).
Steps:
Standardize features.
Apply K-Means with different k values.
Evaluate clusters using Inertia and Silhouette Score.
Evaluation Metrics
Inertia: Measures the sum of squared distances within clusters. Lower is better.
Silhouette Score: Measures how well-defined clusters are. Values closer to 1 are ideal.
Key Findings
Segment 1: Highly engaged customers (more coupons claimed and burned). Target with loyalty programs.
Segment 2: Low coupon usage. Consider offering incentives to increase engagement.
Segment 3: Occasional users. Promotional offers could boost usage.
Segment 4: Balanced coupon usage. Tailor offers to past behavior.
Recommendations:
Target high-engagement customers with exclusive offers.
Incentivize low-engagement customers to use more coupons.
Personalize promotions based on segment behavior.
