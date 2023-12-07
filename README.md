# ShortestBeerDistance
This is the implementation of BUILD-WHL algorithm presented in "Scalable Shortest Beer Path Queries via Highway Labeling" submitted at IEEE International Conference on Data Engineering (ICDE) 2024.
Given a weighted beer graph G=(V,E), it computes a weighted Highway Labeling of G that is exploited at runtime to answer beer distance queries by an ad-hoc query algorithm.
The code extends the implementation of Farhan https://github.com/mufarhan/highway_labelling
The current implementation requires Networkit library https://github.com/networkit/networkit
