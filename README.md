# Point in Polygon

This project shows a visualization of the functioning of 
the algorithm _point-in_polygon_ that determines whether, given a point 
and a polygon, the point is inside or outside it.

## The Algorithm
In computational geometry, the _point-in-polygon_ problem asks whether a given point in the plane lies inside or outside a polygon.
It is a special case of point location problems and finds applications in areas that deal 
with processing geometrical data, such as computer graphics.

The number of intersections for a ray passing from the exterior of the polygon to any point; if odd, it shows that the point lies inside the polygon. If it is even, the point lies outside the polygon; this test also works in three dimensions.

## The limited precision
If implemented on a computer with finite precision arithmetics, 
the results may be incorrect if the point lies very close to that 
boundary, because of rounding errors. 

## The project
The project is a visualization of the algorithm. The visualization was made with the CANVAS element of JavaScript.

![The visualization](index.html)

It's important to note that the variable `precision` can be setted to see te problem of the limited precision.

[This is a project made as an assignment for the Computer Graphics course of FGV-RJ.]