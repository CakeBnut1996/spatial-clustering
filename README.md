# Link Classification Based on Spatial Patterns

Brief description: Customize distance matrix based on road adjacency, daily speed profiles (using dynamic time warping), and geolocations to cluster road networks in order to develop different models to predict future speeds

Objective
- To group links whose have similar traffic patterns together.
- To get more accurate predictions by modeling different patterns separately

Spectral Clustering Attribute: Evaluating whether 2 links are in the same group by
- Similarity of historical daily speed and congestion patterns, 
- Whether belong to the same functional class
- Euclidean distance
- Whether reachable within 20 links

Results: 
![image](https://user-images.githubusercontent.com/46463367/186522572-713ac662-c579-4120-ae94-73901d0d467c.png)



