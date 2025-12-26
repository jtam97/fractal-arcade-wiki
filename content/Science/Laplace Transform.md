---
title: Laplace Transform
---

> [!tip] Information from 3Blue1Brown video series on Laplace Transform

## Notes:

### Basics of Laplace Transform
**Starting off with exponential functions**
- Note that the exponential function e^t is hugely important in explaining Euler's formula. First the derivative of e^t is e^t

Intuition using position and velocity vectors over time
- d/dt e^t = e^t means velocity is always equal to position
- d/dt e^2t = 2e^2t means velocity is always twice the position
- d/dt e^-0.5t = -0.5t e^-0.5t. The velocity vector is backwards and half of the position vector
- Here is the interesting part - d/dt e^it (multiplying by an imaginary number) = i e^it 
	- Geometrically, multiplying i to a vector is like making a 90 degree rotation
	- This means e^it traces a circle as the velocity vector is always perpendicular to the position vector (famously, e^i pi = -1)