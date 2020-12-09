# Software-1-Data-Driven-Immediate-Assembly
This project was driven by the idea of working with inflatable architecture, by creating components shaped by a flexible membrane that holds pressure as well as a set of simple connectors to allow for a full aggregation. 

![text](doc/tetrahedron-grid.jpg)

1. create a 3d tetrahedron checkerboard that allows cells to connect at their vertices only
2. using the boundary of the void you are filling, aggregate the generic cells inside
3. generate flocking simulation based on desired anchor points and other criteria such as overhead coverage, luminosity, and part density
4. the path of the flocking selects which sells are kept
5. remaining cells are broken into four groups based on the number of neighbors; this informs the material property of the components
6. identify connection points between cells, removing any cell that has no neighbor, therefore all cells are in loop with the system
7. each group is processed through an inflation simulation that results in varyng inflated cells with a final result for the system

 ![text](doc/flocking-aggregations.jpg)
