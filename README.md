## Overview
This repository contains code written for my thesis project at the University of Virginia, for which I am developing a library for plotting fractals and functions of a complex variable using NVIDIA graphics cards.

## Domain Coloring
Given a complex number $z$, the function we use produces a color in the $HSL$ color model given by 
```math
\begin{align*} H &= \frac{\arg z}{2\pi} + \frac{1}{2} \\ S &= 1 \\ L &= \frac{2}{\pi}\arctan|z| \end{align*}
```
which we then convert to the $RGB$ model using the procedure detailed by
[Saravanan, Yamuna, and Nandhini](https://ieeexplore.ieee.org/abstract/document/7754179).

## Conformal Mapping
[Mercat](https://en.wikibooks.org/wiki/Fractals/Conformal_map)

## Escape-Time Fractals


### Normalization
In order to avoid color banding,

## To-Do List
0. Finish copying over examples and delete remaining old code
1. Unify domain color and conformal map code as much as possible
2. Reduce file count and move code into src folder
3. Implement plotting for Mandelbrot / escape-time fractals
4. Command line progress bar?
5. Design a way to profile performance
6. Write CPU version and compare performance