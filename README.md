# Data Analyst Nanodegree with OpenClassRooms

At OpenClassrooms, the learning process is project-driven because that’s the fastest way to become proficient and to get some hands-on experiences. 
The Data Analyst degree include 9 projects to get through all the fundamentals of the Data Analyst Role.

<b> Read more on this degree here: https://openclassrooms.com/en/dashboard/paths </b>
  
This repository get through the key learnings related to the Project no.8: Customer Segmentation for Bank Marketing based on credit card data.
🎯 Goal: Create a segmentation of customers based on their credit card utilization for improving Bank marketing strategy.

This project is organized in 2 notebooks.

  1) Exploratory Data Analysis

The data can be found in Kaggle: https://www.kaggle.com/arjunbhasin2013/ccdata

Here we are going through the following steps to clean and prepare the data:
  - Handling outliers
  - Dealing with missing values
  - Check correlations and distributions
  - Log-transformation


  2) Clustering

In this notebook, we use the cleaned data to perform a segmentation with Kmean thanks to the following steps :
  - Define number of clusters based on Elbow and Silhouette methods and apply Kmean.
  - Visualization of key characterictics of clusters to understand the typology of customers.
  - Features importance to highlight the key criteria to segment the customers.
  - Cluster Analysis based on distance between the centroids and statistical tests (Mann-Whitney) to check if all clusters are significant.


