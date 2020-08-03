---
title : Compare
---

## Description

This node compares two values using standard mathematical inequalities
such as >, <, <=, >=, =, != and return `True` if it was satisfied and
`False` if not.

## Inputs

- **A** - The first value.
- **B** - The second value.

## Outputs

- **Result** - The resulted boolean.

## Advanced Node Settings

- **Change Type** - Changes the input type to other data type.

## Note

- **A != B** - Means A does not equal to B
- **A is B** - Unlike A = B, this checks if the inputs are the same object. For
  instance, if two integer lists have the same value and length, it will return
  `False` because they are not the same object even though they have the same
  elements.
- **A is None** - Returns True if the input is empty and doesn't represent a
  data type.
- The type of the data changes automatically when you input a different data
  type.
