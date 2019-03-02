<img alt="" src="https://tigeroakes.com/projects/unity-polygon/logo.png" height="128" width="128">

# Polygon2D Editor for Unity

![Example usage animation](example.gif)

Uses the PolygonCollider2D collider to generate a mesh for a gameobject, 
letting you draw polygonal platforms in the Unity edtior via the Edit Collider button. 
Just drag the script onto your platform GameObject and you're good to go.

This script uses the [Triangulator](http://wiki.unity3d.com/index.php?title=Triangulator) class.

## Installing / Getting started

Just **[download the script](PolygonMesh2D.cs)** and place it somewhere inside your Unity project's assets.
Everything needed in contained within one file. 

Use the component by dragging it onto a GameObject or by using the Add Component dialog. This will automatically add a Polygon Collider 2D component if it isn't already present. 

In the Polygon Collider 2D Component, click the "Edit Collider" button to adjust the shape of the collider. The mesh will autoatically adjust itself to fill the collider.

## Licensing

Licsenced under the [MIT License](./LICENSE).
