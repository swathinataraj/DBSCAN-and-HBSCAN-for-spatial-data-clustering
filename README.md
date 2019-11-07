# DBSCAN-and-HBSCAN-for-spatial-data-clustering

Clustering the accidents based on their positions with the help of DBSCAN and HBSCAN, the two most important algorithms to group spatial data. DBSCAN and HBSCAN algorithms work slightly differently. 

DBSCAN is a density based algorithm – it assumes clusters for dense regions. It only extracts the dense clusters and classifies the sparse points as 'noise'. It takes 'distance'(epsilon) and 'minimum number of neighbours' as it's parameters to form clusters.

HBSCAN, on the other hand, clusters the data points based on it's density and only takes 'minimum cluster size' as it's parameters. This can work well with varying density clusters and we don't need to specift the 'epsilon' parameter.
