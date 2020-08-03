---
title : Delay Time
---

## Description

This node subtracts the *delay* input from the *time* input.

The essence of this subtraction is changing the frame at which an
animation will start when using one of the animation nodes or using the
output in a custom animation node tree. That is because negative values
are clamped to zero in the animation process so subtracting 20 from the
input frame will result in zero for the first 20 frame.

## Inputs

- **Time** - An input time.
- **Delay** - A value to subtract from the time or the frame at which
    the animation will start.

## Outputs

- **Time** - The delayed time.
