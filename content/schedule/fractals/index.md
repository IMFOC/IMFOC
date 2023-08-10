---
title: "Polynomials and fractals"
draft: false
ShowToc: false
math: true
ShowReadingTime: false
summary: "Kael-Mikael Perfekt"
weight: 3
---

Consider the polynomial $f(z) = z^2 - 2$. We think of it as a function, taking a point $z$ of the complex plane into a different point $f(z)$. Given $z$, we also consider the iterations $f^n(z)$ of $z$ under the map $f$. For example, letting $z = 0$ we get 

- $f(0) = -2$, 
- $f^2(0) = f(-2) = 2$, 
- $f^3(0) = f(2) = 2$, etc... 

The next point in the orbit is always obtained by applying $f$ to the previous point. 
 
The *Julia Set* of $f$ consists of all those points $z$ such that the orbit of $z$ remains bounded. The Julia set of $f(z) = z^2 - 2$ is relatively easy to calculate: it is the interval $[-2,2]$. For any other point $z$, the iterates eventually grow larger and larger, tending to infinity. For example, for the imaginary unit $z = i$ we get 

- $f(i) = i^2 - 2 = -1 - 2 = -3$, 
- $f^2(i) = f(-3) = 7$, 
- $f^3(i) = f(7) = 47$, etc...
 
Now, what if we replace $2$ by some other number $c$ and consider the dynamics of the innocuous looking function $f_c(z) = z^2 - c$? Unlike the example above, the Julia set of $f_c$ will typically be a complicated set that is *fractal* in nature. In this talk we will discuss and explore this amazing phenomenon, and the interactions between polynomials and fractals.
 
---

[Karl-Mikael Perfekt](https://kmperfekt.com/) is an associate professor in mathematics at NTNU. His research area is mathematical analysis, a branch of mathematics that deals with limits, approximations, quantities and inequalities.

<img src="images/fractal1.jpg#invert" alt="Error loading image" width="700"/>