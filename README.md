# Bellman-Ford Algorithm
### Computes shortest paths from a single source vertex to all of the other vertices.
See also: [Bellman-Ford algorithm](https://en.wikipedia.org/wiki/Bellman–Ford_algorithm) 

## Input File
Algorithm works perfectly fine with an included preview model in a [G.json](https://github.com/Kojec1/Teoria_Grafow/blob/main/G.json) file, but it is also possible to create own example using given template:

```
[[source node, target node, weight],
[source node, target node, weight],
                .
                .  
                .
[source node, target node, weight]]
```
Where each row represents a directed edge and every node is an integer.

## Results
Algorithm visualize given model and returns list of distances from a source vertex to all of the other vertices.

![Example image](https://github.com/Kojec1/Teoria_Grafow/blob/main/Graph.png "Visualization")

Printed list for a preview model:

```
Distances: [0, 5, 1, 6, 13, 15, 14]
Predecessors: [None, 0, 0, 1, 3, 4, 1]
```
Where each integer is a value for a corresponding node to a value's index. 
For example - shortest distance from a node 0 to a node 5 is 15 units.

## Usage
It is recommended to open .ipynb file with Jupyter Notebook. Other IDEs might require activating jupyter widgets manually (e.g. JupyterLab) or will not support at all.

Clone this repository and open file ```Bellman-Ford.ipynb```, then run each cell in a respective order. 

Make sure every cell is actived!






