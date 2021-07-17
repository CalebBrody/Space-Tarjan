# Space-Tarjan
A short Python notebook to visualize Tarjan's algorithm for finding choke points in video games. 

Tarjan's algorithm finds choke points or “bridges” between two sub graphs only traversing each edge once. It does this by storing two pieces of information regarding each edge: the first time reached (TTR) and the min TTR of every point reachable by that point. Any edge where the later is greater than the former is a bridge. 

This notebook visualizes the discovery process by displaying each value on the grid at each update step. 

Examples 

One 
![one.gif](Generation1.gif)

Two 
![two.gif](Generation1.gif) 
