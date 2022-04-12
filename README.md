# Credit Card Users Clustering - Overview
This peoject was done on the dataset obtained from Kaggle
<br>Created a model that uses k-means clustering to group the data into clusters
## Code and Resources Used
Python Version: 3.7
Packages: pandas, numpy, sklearn, matplotlib, seaborn

## Project Methodology

- After loading the libraries and data, the intial exploration of the data was done
- Cust-ID column was dropped as it was not required for analysis
- Data was scaled
- Dimensionality of data was reduced for kmeans clustering
- Number of clusters were determined based on the elbow method
- Clustering was done on the scaled data with the number of clusters determined from the elbow method
- Different clusters were vizualized using FacetGrid from Seaborn
## Observations
1. Cluster0 People with average to high credit limit who take advance cash more often but don't make as many purchases
2. Cluster1 Less money spenders with low to average credit limits who purchases mostly in installments
3. Cluster2 This group uses their credit cards for one off purchases, they mostly have average to high credit limits
4. Cluster3 People with low to average credit limit who use their credits frequently for all types of purchases and cash advance
5. Clusters 3 is the biggest followed by cluster 1.
