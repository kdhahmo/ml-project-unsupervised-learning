# Machine Learning Project: Unsupervised Learning

## Project Goals
Perform unsupervised learning techniques on a real-world wholesale data dataset.
1. exploratory data analysis and pre processing
2. kmeans clustering
3. hierarchical clustering
4. principal component analysis


## Process
The detailed process for this project can be found in the ["Unsupervised Learning - Project"](<Unsupervised Learning - Project.ipynb>) notebook.

### 1. exploratory data analysis and pre processing

- bring in the ["Wholesale Data"](Wholesale_Data.csv) dataset
- check the data for duplicates and nulls
- check the correlation between columns and decide on what column to keep in this case
- check for outliers
- remove identified duplicates, nulls, and outliers

### 2. kmeans clustering

- perform k means clustering on the cleaned data
- determine the characteristics of these k means clusters and what information we can use this clustered data for

### 3. hierarchical clustering

- perform hierarchical clustering on the cleaned data
- determine the characteristics of these hierarchical clusters and what information we can use this clustered data for

### 4. principal component analysis

- perform principal component analysis
- draw conclusions on the structure of the data

## Conclusions

- The KMeans distribution shows that clients can be grouped into 13 distinct clusters; some clients are in a group of a few; others in a group of many that are similar to them.
- The Hierarchical distribution shows that clients can be grouped into 3 distinct clusters; around 250 clients are in the majority group; around 125 are in a less populated but well represented group; around 25 are in a distinct group.
- K Means has more distinct granular groups of clients whereas Hierarchical Clustering has groups of clients that can be used more generally and have more data to pull from.
- We can graph the distributions of each cluster to see differences in clients and determine ways to market to or plan purchases for them.

