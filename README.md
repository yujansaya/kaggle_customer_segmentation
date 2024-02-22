Mall Customer Segmentation with K-Means and Hierarchical Clustering applying PCA, and further Data visualization.

Kaggle dataset

Import Context This data set is created only for the learning purpose of the customer segmentation concepts , also known as market basket analysis . I will demonstrate this by using unsupervised ML technique (KMeans Clustering Algorithm) in the simplest form.

Content You are owing a supermarket mall and through membership cards , you have some basic data about your customers like Customer ID, age, gender, annual income and spending score. Spending Score is something you assign to the customer based on your defined parameters like customer behavior and purchasing data.

Problem Statement You own the mall and want to understand the customers like who can be easily converge [Target Customers] so that the sense can be given to marketing team and plan the strategy accordingly.


This Python code performs customer segmentation using K-Means and Hierarchical Clustering techniques, along with Principal Component Analysis (PCA) for dimensionality reduction and data visualization. Here's a brief summary of each section:

Importing Libraries: The code imports necessary libraries such as NumPy, Pandas, Matplotlib, Seaborn, and scikit-learn modules for data processing, clustering, and visualization.

Data Preprocessing: It loads the dataset containing customer information (Customer ID, age, gender, annual income, and spending score), checks for missing or duplicated values, and performs basic data exploration.

Data Visualization: Visualizations like histograms, box plots, and pair plots are created to understand the distribution and relationships between different features in the dataset.

Feature Encoding and Scaling: The 'Gender' feature is encoded using LabelEncoder and the dataset is standardized using StandardScaler for further analysis.

Principal Component Analysis (PCA): PCA is applied to reduce the dimensionality of the dataset, both for all features and specifically for the 'Annual Income' and 'Spending Score' features.

K-Means Clustering: The Elbow Method is used to determine the optimal number of clusters, and then K-Means clustering is performed on both the original and PCA-transformed datasets.

Hierarchical Clustering: Hierarchical clustering is applied with a chosen number of clusters, using both the original and PCA-transformed datasets.

Visualization of Clusters: Clusters obtained from both K-Means and Hierarchical clustering are visualized using scatter plots, with centroids highlighted.

Prediction: A single sample is used to make predictions using both K-Means and Hierarchical clustering.

Analyzing Predictions: The predictions obtained from clustering are visualized using pair plots to observe how well the clusters separate different groups of customers based on their features.

Overall, the code demonstrates how to perform customer segmentation using unsupervised machine learning techniques and visualize the results to gain insights into customer behavior and preferences.
