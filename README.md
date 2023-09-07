# Iris Flower Clustering Using K-Means

This repository contains a Jupyter Notebook (GRIP TSF Task-02.ipynb) that demonstrates an unsupervised machine-learning task using Python and Scikit-Learn. The task involves clustering iris flowers into distinct groups using the K-Means clustering algorithm.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Data Loading](#data-loading)
- [Data Preprocessing](#data-preprocessing)
- [Determining Optimal Clusters](#determining-optimal-clusters)
- [K-Means Clustering](#k-means-clustering)
- [Cluster Visualization](#cluster-visualization)
- [Silhouette Score](#silhouette-score)
- [Conclusion](#conclusion)

## Introduction

This project explores unsupervised machine learning techniques, specifically K-means clustering, to group iris flowers into clusters based on their features. The code is implemented in Python and uses libraries such as NumPy, pandas, matplotlib, and Scikit-Learn.

## Getting Started

To run this project, you can use a Jupyter Notebook environment. The notebook is self-contained and can be executed cell by cell. The code is also hosted on Google Colab, making it easy to run and experiment with. You can access the original notebook at [this link](https://colab.research.google.com/drive/1UP-qFxheZDeDM1m01UuiEUrk9qAdMetj).

## Data Loading

The project starts by loading the famous Iris dataset from Scikit-Learn. The dataset contains measurements of iris flowers' sepal length, sepal width, petal length, and petal width, along with their corresponding species labels. The data is displayed in a DataFrame.

## Data Preprocessing

Before clustering, feature scaling is applied to ensure that all features have similar ranges. The scaled data is displayed in a separate DataFrame for reference.

## Determining Optimal Clusters

The optimal number of clusters is determined using the Elbow Method. The within-cluster sum of squares (WCSS) is plotted against the number of clusters to identify an "elbow point" where the rate of decrease in WCSS slows down.

## K-Means Clustering

K-means clustering is applied with the chosen optimal number of clusters. The algorithm assigns each data point to one of the clusters.

## Cluster Visualization

Clusters are visualized using a scatter plot. Different colors represent different clusters, and the centroids of each cluster are also marked on the plot.

## Silhouette Score

The Silhouette Score is calculated to assess the quality of clustering. This metric measures the similarity of data points within the same cluster compared to other clusters.

## Conclusion

This project demonstrates the application of K-Means clustering to group iris flowers based on their features. It provides insights into data preprocessing, cluster determination, visualization, and cluster quality assessment. The Silhouette Score helps evaluate the effectiveness of the clustering. You can further explore and modify the code for similar clustering tasks.
