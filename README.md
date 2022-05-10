# Classic-Algorithm-pt.2
Second classic alogorithm: Minimum Cost Spanning Tree

A Minimum Cost Spanning Tree (MCST) is a form of input that handles undirected weighted graphs. The minimum cost is determined by summing the values for all edges in the 
subset. The vertices are connected. It represents a free tree with V-1 edges. 

Prim’s algorithm is another approach like Dijkstra’s algorithm. Prim’s algorithm starts with any vertex N in graph G. it then picks the least cost edge connected to N 
this is referred as M. add M and Edge(N,M) to the graph. Then pick the least cost edge from N or M to the other vertex. then add the new vertex and edge to MCST. This 
process is done until all vertices are VISITED. (Prim’s algorithm is also important to the creation of the code).
