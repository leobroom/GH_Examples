# RTree
![Alt text](img/rTreeExample.png?raw=false "rTree Class in Grasshopper/ Rhino")
## Summary
From the RhinoCommon:
"RTree represents a spatial search structure based on implementations of the R-tree algorithm by Toni Gutman."

The example shows a simple distance calculation.

## Explanation
What does the examples do?

The rTree C# component outputs all points (yellow) from a point collection located within a cylinder.

To speed up the distance calculation, a rTree is used. This allows us to reduce the search space by including a bounding box. (blue)

For more information visit the awesomewebsite of Luis Quinones:
http://www.complicitmatter.com/PORTFOLIO/gallopingtopiary/

## Links
https://en.wikipedia.org/wiki/R-tree
https://developer.rhino3d.com/api/RhinoCommon/html/T_Rhino_Geometry_RTree.htm
https://developer.rhino3d.com/samples/rhinocommon/closest-point-calculation-with-rtree/
