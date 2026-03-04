Customer Segmentation using K-Means Clustering
1. Project Overview

Customer segmentation is a fundamental task in marketing analytics that helps businesses understand customer behavior and group customers with similar characteristics.

This project applies the K-Means clustering algorithm to segment mall customers based on their demographic and spending patterns. The objective is to identify distinct customer groups that can help businesses design targeted marketing strategies and improve customer engagement.

2. Business Problem

Businesses often deal with large customer bases with varying spending behaviors. Without segmentation, it is difficult to design personalized marketing strategies.

By grouping customers with similar characteristics, businesses can:

Identify high-value customers

Develop targeted marketing campaigns

Improve customer retention

Optimize promotional strategies

This project demonstrates how machine learning can assist in customer behavior analysis.

3. Dataset Description

The dataset used in this project is the Mall Customers dataset, which contains demographic and spending information for customers visiting a shopping mall.

Dataset Characteristics

Number of records: 200

Number of features: 5

Features
Feature	Description
CustomerID	Unique identifier assigned to each customer
Gender	Gender of the customer
Age	Age of the customer
Annual Income (k$)	Customer's annual income measured in thousands of dollars
Spending Score (1–100)	Score assigned by the mall based on customer spending behavior
4. Methodology

The project follows a structured data science workflow:

Data Exploration

Understanding dataset structure

Summary statistics

Checking missing values

Data Visualization

Scatter plots

Distribution analysis

Feature relationship visualization

Feature Selection

Customer segmentation is performed primarily using:

Annual Income

Spending Score

Clustering Model

The K-Means clustering algorithm is applied to group customers into clusters based on similarities in their spending behavior.

Optimal Cluster Selection

The Elbow Method is used to determine the optimal number of clusters.

5. Model Implementation

The clustering process includes the following steps:

Data loading and preprocessing

Feature selection

Applying the Elbow Method

Training the K-Means clustering model

Assigning cluster labels to customers

Visualizing customer segments

6. Results

The K-Means algorithm successfully identifies multiple customer segments based on income and spending patterns.

Example customer segments include:

High income – high spending customers

High income – low spending customers

Low income – high spending customers

Low income – low spending customers

These segments help businesses identify premium customers and potential marketing targets.

7. Visualization

The project includes visualizations such as:

Elbow Method plot for optimal cluster selection

Scatter plots showing cluster distribution

Cluster labeling visualization

These plots help interpret the clustering results effectively.

8. How to Run the Project

Clone the repository:

git clone https://github.com/YashasD11/Customer-Segmentation.git

Navigate to the project directory:

cd customer-segmentation

Install required libraries:

pip install -r requirements.txt

Run the notebook:

jupyter notebook

Open and execute:

Kmeans.ipynb
9. Technologies Used

Python

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

Jupyter Notebook

10. Applications

Customer segmentation models like this are used in:

Retail analytics

Marketing campaign design

Customer lifetime value analysis

Product recommendation systems

Targeted advertising
