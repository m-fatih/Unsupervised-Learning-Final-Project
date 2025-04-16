# Unsupervised-Learning-Final-Project
Final project for Unsupervised Learning: Clustering the Ames Housing dataset

# Ames Housing Market Segmentation (Unsupervised Learning Final Project)

## Problem Statement
This project explores the Ames Housing Dataset to uncover natural clusters of homes based on physical and categorical attributes — such as age, size, and quality — without using price labels. The goal is to apply unsupervised learning techniques to segment the housing market and identify interpretable groups of similar properties.

## Data Source
- [Ames Housing Dataset on Kaggle](https://www.kaggle.com/datasets/shashanknecrothapa/ames-housing-dataset)  
- De Cock, D. (2011). *Ames, Iowa: Alternative to the Boston Housing Data*. Journal of Statistics Education.

## Methods
- Data Cleaning with Domain-Aware Imputation
- Feature Engineering: House_Age, Total_SF, Total_Bathrooms, Has_Pool
- Exploratory Data Analysis (Histograms, Correlation Matrix, PCA Scree Plot)
- PCA for Dimensionality Reduction and Visualization
- Clustering with KMeans and Agglomerative Clustering
- Comparison of Cluster Results
- Interpretation of Clusters using Summary Statistics and Bar Charts

## Results
- Identified 4 meaningful housing clusters ranging from luxury newer homes to historic modest properties
- KMeans and Agglomerative Clustering yielded consistent, stable segmentation
- PCA enabled effective 2D visualization of clusters

## Takeaways
- Feature engineering played a crucial role in meaningful segmentation
- Unsupervised learning can reveal interpretable structure even without labeled data
- Future work may explore DBSCAN, geographic coordinates, or dashboard deployment

## Files Included
- `Unsupervised_Learning_Final_Project.ipynb`: Main notebook
- `AmesHousing.csv`: Dataset used for modeling
- `README.md`: This file
