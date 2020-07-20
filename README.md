# Clustering News with Expectation Maximization

<img src="https://i.imgur.com/U3lsSMA.png" width="400">


In this project we apply clustering techniques to cluster data from the BBC dataset. Our goal is to identify patterns of news without using labels. The approach we will follow for EM in this project follows the work developed by professor [Gholamreza Haffari](http://users.monash.edu.au/~gholamrh/) from Monash University. 


## Expectation Maximization for Document Clustering

From [rapidminer](https://docs.rapidminer.com/latest/studio/operators/modeling/segmentation/expectation_maximization_clustering.html)
*The EM (expectation maximization) technique is similar to the K-Means technique. The basic operation of K-Means clustering algorithms is relatively simple: Given a fixed number of k clusters, assign observations to those clusters so that the means across clusters (for all variables) are as different from each other as possible. The EM algorithm extends this basic approach to clustering by assigning examples to clusters to maximize the differences in means for continuous variables.The EM clustering algorithm computes probabilities of cluster memberships based on one or more probability distributions. The goal of the clustering algorithm then is to maximize the overall probability or likelihood of the data, given the (final) clusters.*


## Datasets

A public dataset from the BBC comprised of 2225 articles, each labeled under one of 5 categories: business, entertainment, politics, sport or tech. The dataset is broken into 1490 records for training and 735 for testing. Available in [kaggle](https://www.kaggle.com/c/learn-ai-bbc)


## Visuals / Results

We achieve good results with similar patterns to those of the labelled data. 
![Imgur](https://i.imgur.com/nofzeNv.png)
