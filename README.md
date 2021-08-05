# Python_Dijkstra
A visualization of Dijkstra's Algorithm for finding the best path to a solution creating in Python with Pygame.

Definition of Dijkstra's Algorithm
----------------------------------
Dijkstra's algorithm uses a data structure for storing and querying partial solutions sorted by distance from the start. While the original algorithm uses a min-priority queue and runs in time {\displaystyle \Theta ((|V|+|E|)\log |V|)}{\displaystyle \Theta ((|V|+|E|)\log |V|)}(where {\displaystyle |V|}|V| is the number of nodes and {\displaystyle |E|}|E| is the number of edges), it can also be implemented in {\displaystyle \Theta (|V|^{2})}{\displaystyle \Theta (|V|^{2})} using an array.
The algorithm exists in many variants. Dijkstra's original algorithm found the shortest path between two given nodes,[6] but a more common variant fixes a single node as the "source" node and finds shortest paths from the source to all other nodes in the graph, producing a shortest-path tree.
