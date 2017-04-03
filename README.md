# kmeans

# Overview of Project
• Given a collection of dataset <br />
• Our group implemented some algorithm to analyze the dataset
• Compare and contrast with another existing algorithm

# Lloyd’s k-means algorithm
Lloyd’s algorithm is based on simple observation that the optimal placement of a center is at the centroid of the associated cluster. Each stage of Lloyd’s algorithm moves every center point z to the  centroid v(z) and then updates  v(z) by recomputing the distance from each point to its nearest center. This step is repeated until the best condition is met.

# Our Approach
Basically we used the same algorithm as what is mentioned inside Lloyd’s algorithm, to analyze given datasets with data mining approach, we calculate the lowest Sum of Squared Error for the nearest distance/proximity between coordinates as the result. We do it by Randomly select data points as the cluster centers, We will then assign nearest data points to the centroids by the proximity measures (Euclidean Distance), Calculate SSE and update the Centroid, These steps are repeat until the Centroid didn’t move.

# Why K-means?
> We believe K-means would be the easiest to implement.
> K-means provides the most accurate findings
> K-means enumerate all possible combinations of clusters
> Disadvantage
  > K-means only limited to numerical value
> Our data only have 4898 instances with 12 Attributes
> and all attributes are in numerical value (decimals)
> It is efficient to use K-means to cluster

# Input
> Data Points
  > winequality-white.csv
> K number of clusters
  > K = 4
> Proximity Measure
  > Euclidean Distance
> Clustering Criterion function
  > Sum of Square Error
  
# Algorithm
> Randomly select data points as centroids
> Assign nearest data point to cluster centers
> Calculate the SSE of the clusters
> update Centroids
> Repeat until SSE stay constant.

# Output / Findings
> With the same iteration to cluster data using k-means algorithm
> SSE score from WEKA: 450.63935732694006
> SSE score from our algorithm: 425.66950880825095
> We find the SSE score based on our algorithm output is close to WEKA’s output 
