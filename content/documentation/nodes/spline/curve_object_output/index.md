---
title : Curve Object Output
---

## Description

This node takes a list of splines and write them to a curve object. It
is possible to insert a single spline because the node is vectorized.

## Inputs

- **Splines** - A list of splines that form the curve.
- **Bevel Depth** - The radius of curve.
- **Bevel Resolution** - An integer that defines the number of vertices of the
  curve. Notice that the original number of vertices of the curve is 4 and the
  integer defines the extra number of vertices to be added.
- **Extrude** - Amount of extrusion applied to the curve.
- **Bevel Start** - A factor that defines the start of beveling.
- **Bevel End** - A factor that defines the end of beveling.
- **Offset** - The amount of offset applied to the curve.
- **Preview Resolution** - The quality of the curve. (The number of loops that
  connect the two handles)
- **Taper Object** - A curve to use as a factor for the radius of the curve.
- **Bevel Object** - A curve to use as a shape for the curve.
- **Fill Mode** - A string that defines the mode for filling the curve,
  Possible modes can be known from the advanced node setting panel.

## Outputs

- **Object** - The output curve.
