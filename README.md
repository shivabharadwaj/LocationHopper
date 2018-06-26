Title: Location Hopper

Names: Pranab Krishnan, Sid Jaiswal, Shiva Bharadwaj

Category: Empirical Analysis - We will be using Yelp and Google Maps data to help users plan a trip to highly rated attractions of the user’s choice around an inputted address. 

Description: 
Graph Algorithms and Document Search to find ratings and distances. We will be representing locations as nodes and a pre-defined Score as edge weights. This Score was calculated by subtracting the average of the ratings of the two locations being connected from the distance between the two and adding a constant to ensure positive edge-weights.

The key to finding the least-weighted path between all of them is using Dijkstra’s algorithm to find the locations closest to each other in Score in order to recommend a trip including five of the highest rated attractions as possible.

We will take in the location of the hotel the user is staying at and output our five recommended attractions to visit determined by Yelp rating and distance. 

Work Partition:

Working with Yelp API: Pranab

Working with Google API: Sid & Shiva

Creating Score algorithm & Dijkstra’s implementation: All
