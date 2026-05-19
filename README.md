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
The project begins by importing the Mall Customers dataset and loading it into Python using Pandas for data manipulation and analysis. Initial data exploration was performed to understand the structure of the dataset, identify important features, and check for missing values or inconsistencies. Exploratory Data Analysis (EDA) techniques such as summary statistics and visualizations were used to analyze customer demographics, annual income, and spending behavior.

After preprocessing, the relevant features including Annual Income and Spending Score were selected for clustering. Since clustering algorithms are sensitive to feature scales, the data was normalized using StandardScaler to ensure all variables contributed equally to the model.

Next, the K-Means Clustering algorithm was applied to group customers into different segments based on similarities in purchasing patterns. To determine the optimal number of clusters, both the Elbow Method and Silhouette Score Analysis were used. Multiple K values were tested, and the model achieved the best Silhouette Score at K = 6, indicating the most effective customer segmentation.

Finally, the customer clusters were visualized using scatter plots and data visualization libraries such as Matplotlib and Seaborn. The resulting segments provided meaningful business insights, helping identify high-value customers, low-spending customers, and potential target groups for personalized marketing strategies.


Key Insights :
High-income customers with high spending behavior form premium customer segments.
Some customers have high income but low spending, indicating potential marketing opportunities.
Customer groups show clear purchasing patterns useful for targeted campaigns.

Results : 
The K-Means clustering model successfully segmented customers into 6 distinct groups based on their Annual Income and Spending Score. The optimal number of clusters was determined using the Elbow Method and Silhouette Score Analysis.
Among all tested K values, the model achieved the highest Silhouette Score of 0.4311 at K = 6, indicating effective cluster separation and better grouping performance.

The final clusters helped identify different customer categories such as:
High-income high-spending customers
High-income low-spending customers
Moderate-income moderate-spending customers
Low-income low-spending customers
These customer segments can help businesses improve targeted marketing, customer retention strategies, and personalized recommendations.

Visualizations :
The project uses data visualizations to analyze customer behavior and clustering performance. The Elbow Method was used to identify the optimal number of clusters by analyzing WCSS values, while Silhouette Score Analysis evaluated cluster quality and separation. Final scatter plots were created to visualize customer segments based on Annual Income and Spending Score.

Future Improvements :
Apply DBSCAN and Hierarchical Clustering, 
Deploy as a Streamlit Web App, 
Add customer recommendation system,
Perform real-time segmentation.

