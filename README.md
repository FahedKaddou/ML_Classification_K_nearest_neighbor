# ML_Classification_K_nearest_neighbor
Use K Nearest neighbors to classify data

# Table of contents
- Load Data From CSV File
- Data Visualization and Analysis
- Normalize Data
- Training
- Predicting
- Accuracy evaluation
- Plot the model accuracy for a different number of neighbors.

# Objectives
We will load a customer dataset, fit the data, and use K-Nearest Neighbors to predict a data point.

# About the dataset
Imagine a telecommunications provider has segmented its customer base by service usage patterns, categorizing the customers into four groups. If demographic data can be used to predict group membership, the company can customize offers for individual prospective customers. It is a classification problem. That is, given the dataset, with predefined labels, we need to build a model to be used to predict class of a new or unknown case.
The example focuses on using demographic data, such as region, age, and marital, to predict usage patterns.
The target field, called custcat, has four possible values that correspond to the four customer groups, as follows: 1- Basic Service 2- E-Service 3- Plus Service 4- Total Service.
Our objective is to build a classifier, to predict the class of unknown cases. We will use a specific type of classification called K nearest neighbour.

# Downloading the Data
Let's download the dataset: 'https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-ML0101EN-SkillsNetwork/labs/Module%203/data/teleCust1000t.csv'
