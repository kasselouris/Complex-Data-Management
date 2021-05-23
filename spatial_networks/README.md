## california_road_network.py

Creates a data structure that holds for all the nodes from California Road Network its coordinates and an adjacency list with all its neighbor nodes and their edge distance from them. It then outputs this data structure on out.txt.

The data about the Californias Road Network and an example *out.txt* are in the [assets folder](https://github.com/kasselouris/Complex-Data-Management/tree/main/spatial_networks/assets) and are based on [this data set](http://www.cs.utah.edu/~lifeifei/SpatialDataset.htm).

The first line of *out.txt* is:
> 0 -121.904167 41.974556 1 0.002025 6 0.005952 

and is meant to be readed like node 0 with latitude -121.904167 and longtitude 41.974556 has node 1 as neighbor with edge distance 0.002025 and node 6 with edge distance 0.005952.

## dijkstra_Astar.py

Based on the Californias Road Network above we find the shortest path distance between two nodes of the graph using two popular algorithms, [Dijkstra](https://en.wikipedia.org/wiki/Dijkstra%27s_algorithm) and [A*](https://en.wikipedia.org/wiki/A*_search_algorithm) shortest path algorithms.

## topK_NRA.py

Based on the Californias Road Network above we find the best meeting node for a set of starting nodes. The best meeting node must selected so as the max shortest path distance from a starting node to this node is the smallest possible. Dijkstras shortest path and top K NRA algorithm are used. 
