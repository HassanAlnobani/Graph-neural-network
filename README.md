# Graph-neural-network
Simple Graph Creation:

Creates a simple graph with three nodes and three edges.
Visualizes the graph using matplotlib.

Adding Edges and Visualizing:
Adds more edges to the existing graph, creating a complex structure.
Visualizes the updated graph in green.

Edge Betweenness Centrality:
Calculates the edge betweenness centrality of the graph.
Identifies edges crucial for connecting different parts of the graph.

Iterative Removal of Edges:
Iteratively removes edges with the highest betweenness centrality.
Visualizes the graph after each removal in red.

Barabasi-Albert Graph:
Generates a Barabasi-Albert graph with 100 nodes and 2 edges per node.
Visualizes the graph using a spring layout.
Plots histograms of closeness centrality and betweenness centrality.

Social Network Analysis:
Loads data from CSV files containing information about a hero network.
Selects subsets of heroes (Thor, Captain America, Iron Man).
Creates a graph from the subset and visualizes it.
Calculates betweenness centrality for each node.

Printing Top Connectors:
Prints nodes with the highest betweenness centrality, indicating their importance in connecting the network.

Clustering Coefficients:
Calculates the clustering coefficient for each node in the graph.
