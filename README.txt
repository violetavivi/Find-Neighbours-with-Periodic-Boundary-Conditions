# Find-Neighbours-with-Periodic-Boundary-Conditions
Collection of Matlab functions to find neighbours in 2D matrices with Periodic Boundary Conditions

#What are Periodic BOundary Conditions?
Periodic Boundary Conditions (PBCs) are a set of boundary conditions which are often chosen for
approximating a large (infinite) system by using a small simulation box (our matrix).
An object which has passed through one limit of the simulation box re-enters through the opposite face. 
Thus, if a 2D matrix is used as simulation box, the real topology is a torus. (Wikipedia)
Ex: if an object is moving in a NxN simulation box and its next coordinate happens to be [N+1,5], it is corrected to [1,5].

#Functions:

#Find8Neighbours
It finds the nearest neighbours of a square 2D matrix element with PBCs

#FindAllNeighsPBC: 
It finds all the neighbours of a square 2D matrix element with PBCs at certain distance radio (it can be the whole matrix).
Here, distance is just the number of  elements. (More info in file).

#Violeta Calleja Solanas 2017/03/24
