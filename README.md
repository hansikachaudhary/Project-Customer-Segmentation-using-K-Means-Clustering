# Project---> CUSTOMER SEGMENTATION USING K-MEANS CLUSTERING
Customer segmentation is an essential technique for businesses to classify their customers based on purchasing behavior, income, and spending patterns. This project implements K-Means Clustering to group customers into distinct segments, enabling businesses to tailor their marketing strategies effectively.

-----------------------------------------------------------------------------------------------------------------
# OBJECTIVE:
The goal of this project is to analyze customer data and identify different groups with similar characteristics. This helps businesses personalize their services, optimize marketing campaigns, and improve customer engagement.

------------------------------------------------------------------------------------------------------------------
# TECHNOLOGIES USED:

--> Programming Language: Python
--> Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
--> Algorithm Used: K-Means Clustering

------------------------------------------------------------------------------------------------------------------

# DATASET:
The dataset used contains 200 customer records with the following attributes:

Customer ID
Gender
Age
Annual Income (k$)
Spending Score (1-100)

-------------------------------------------------------------------------------------------------------------------

# METHODOLOGY:
1.  Data Collection & Preprocessing:

Loaded data from a CSV file using Pandas
Checked for missing values (none found)
Selected Annual Income and Spending Score as features for clustering

2.  Finding the Optimal Clusters:

Used the Within-Cluster Sum of Squares (WCSS) method
Applied the Elbow Method to determine the optimal number of clusters (5)


3.  Implementing K-Means Clustering:

Initialized K-Means with k=5 and k-means++ initialization
Fit the model to the data and assigned clusters


4.  Visualization of Clusters:

Used scatter plots to display customer groups
Plotted cluster centroids for better interpretation

----------------------------------------------------------------------------------------------------------------------

# RESULTS & INSIGHTS:
Customers were successfully segmented into five groups based on their income and spending behavior.
The segmentation helps in targeting high-spending customers, budget shoppers, and mid-range spenders with tailored strategies.
Businesses can use these insights to optimize advertising, improve retention, and increase sales.

----------------------------------------------------------------------------------------------------------------------


# CONCLUSION:
This project demonstrates the power of unsupervised machine learning in customer analytics. By implementing K-Means clustering, businesses can better understand customer behavior and make data-driven decisions.
