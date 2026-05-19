# Customer-Segmentation-Using-K-Means-Clustering
Customer Segmentation using K-Means Clustering
Project Overview : 
This project performs Customer Segmentation using the K-Means Clustering algorithm to identify distinct customer groups based on purchasing behavior and annual income.
The objective is to help businesses understand customer patterns and improve marketing strategies through data-driven segmentation.

Problem Statement :
Businesses often struggle to identify different customer types within large datasets. This project applies unsupervised machine learning to group customers with similar characteristics, enabling targeted marketing and better business decisions.

Dataset : Mall Customers Dataset
Source: Kaggle 
Features Used
Customer ID
Gender
Age
Annual Income (k$)
Spending Score (1-100)

Technologies Used : 
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook

Machine Learning Technique
K-Means Clustering
K-Means is an unsupervised machine learning algorithm used to divide customers into multiple clusters based on similarities.

Data Preprocessing
Data Cleaning
Feature Selection
Standard Scaling

Optimal Cluster Selection : 
Elbow Method
Silhouette Score Analysis

Project Workflow :
Import Dataset
Perform Exploratory Data Analysis (EDA)
Select Important Features
Normalize Data using StandardScaler
Apply K-Means Clustering
Find Optimal K Value
Visualize Customer Segments
Generate Business Insights

Key Insights :
High-income customers with high spending behavior form premium customer segments.
Some customers have high income but low spending, indicating potential marketing opportunities.
Customer groups show clear purchasing patterns useful for targeted campaigns.

Results : 
Optimal Clusters Identified: 6
Best Silhouette Score Achieved: 0.4311
Silhouette Scores
K Value	Score
2	0.3355
3	0.3579
4	0.4040
5	0.4085
6	0.4311

Visualizations :
Elbow Method
Customer Clusters

Future Improvements :
Apply DBSCAN and Hierarchical Clustering
Deploy as a Streamlit Web App
Add customer recommendation system
Perform real-time segmentation

