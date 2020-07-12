---
title : Line Mesh
weight : 10
---

## Description

This node return the mesh of a line based on an input starting
point and an input ending point.

## Options

- **Line Mode**
    - *Start-End* - This option allows to generate line mesh from start and end vectors.
    - *Points* - This option allows to generate line mesh from a vector list.

## Inputs

- **Start** - A vector that define the starting point of the line.
- **End** - A vector that define the ending point of the line.
- **Steps** - An integer that define the number of vertices that form
    the line.
- **Cyclic** - A boolean value that make the output mesh cyclic.

## Outputs

- **Mesh** - The mesh.
