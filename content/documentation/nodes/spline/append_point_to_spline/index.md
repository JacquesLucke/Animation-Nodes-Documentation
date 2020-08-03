---
title : Append Point To Spline
---

## Description

This node adds a new point to the input spline.

## Options

- **Point** - This option will add a point with a linear handle (A non
    bezier point).
- **Bezier Point** - This option will add a bezier point which have a
    left and right handle.

## Inputs

- **Spline** - A spline to add the point to.
- **Point** - The position of the point that will be added.
- **Left Handle** - The position of the left handle of the bezier
    point. (Only in the **Bezier Point** option)
- **Right Handle** - The position of the right handle of the bezier
    point. (Only in the **Bezier Point** option)
- **Radius** - The radius of the point.

## Outputs

- **Spline** - The output spline.
