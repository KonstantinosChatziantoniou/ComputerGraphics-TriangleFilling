# ComputerGraphics-TriangleFilling
Using scanline algorithm for triangle filling and flat coloring or Gouraud shading


In this assignment, the *polygon-filling* **scanline** algorithm is implemented for the special case of triangles. The points of the triangle are either filled with flat color or by using **Gouraud** shading.

### Demos

Given a set of triangles (edges, edge color, edge depth) and their projection to 2d an image is contructed.

+ **demoFlat.m** Flat coloring - mean of the edge colors for each triangle.
+ **demoGouraud** Gouraud shading - linearly interpolating vertex colors from edge color, and then linearly interpolating scan line colors from active points of active vertex.

### Input

duck_hw1.mat is given as an example. Study its structure and modify demo scripts for different input.

### Output

Both demos save the constructed image as jpeg. By uncommenting the **imshow** lines you can plot the result in Matlab

For more information see the *report.pdf*
