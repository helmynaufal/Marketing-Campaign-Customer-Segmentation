# Marketing-Campaign-Customer-Segmentation

## Overview
A company can grow rapidly when they know how their customer behaves, so they can provide better service and benefits to the customer that have the potential to be loyal customers. By processing historical marketing campaign data, a company can improve its performance and target the right customers so they can make transactions on the company's platform. From this data insight, we can focus on creating a cluster prediction model to make it easier for companies to make decisions.

## The Steps Involved
Here is the list of the steps involved in this project.

**1. Data Exploration**
First, we will explore the data to understand the meaning of each column in the dataset, find any patterns and gain insight from the data.

**2. Preprocessing**
There are several steps we do during the preprocessing:
- Data Cleaning: Clean data from missing values and duplicate data.
- Feature Selection: Remove unnecessary features.
- Feature Encoding: Transform the categorical values into numerical ones.
- Feature Transformation: Transform the data to the normal distribution.

**3. Data Modeling**
Here, we will create, compare, and evaluate our machine-learning models. We will perform clustering in the following steps:
- Perform dimensionality reduction using Principal Component Analysis (PCA)
- Determine the number of the cluster using Elbow Method
- Label the customer cluster using K-Means Clustering
- Evaluate the model using Silhouette Score.

**4. Interprating Cluster**
After 4 clusters are created, we will do several data exploratory then we can conclude the profile of each cluster as follows:
- High Spender
- Moderate Spender
- Low Spender
- Risk of Churn

**5. Recommendation**
Finally, after we understand the profile of each cluster, we provide some recommendations that can be used for the marketing campaign.
