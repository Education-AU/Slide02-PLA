---
title: Change to standard basis
template: default
---

A very important fact is if we use the transformation in the other direction we should get back the same coordinates.

In matrix formulation the transformation from basis $(1,0),(0,1)$ to $(1,1),(-1,1)$ is

$$
\begin{bmatrix}
d_1\\
d_2
\end{bmatrix}
=
\begin{bmatrix}
\frac{1}{2}& \frac{1}{2}\\
-\frac{1}{2}& \frac{1}{2}
\end{bmatrix}
\begin{bmatrix}
c_1\\
c_2
\end{bmatrix}
$$

And in matrix formulation the transformation from basis $(1,1),(-1,1)$ to $(1,0),(0,1)$ is
$$
\begin{bmatrix}
c_1\\
c_2
\end{bmatrix}
=
\begin{bmatrix}
1& -1\\
1& 1
\end{bmatrix}
\begin{bmatrix}
d_1\\
d_2
\end{bmatrix}
$$
This must imply that
\$$
\begin{bmatrix}
1& -1\\
1& 1
\end{bmatrix}
\begin{bmatrix}
\frac{1}{2}& \frac{1}{2}\\
-\frac{1}{2}& \frac{1}{2}
\end{bmatrix}
=
\begin{bmatrix}
1& 0\\
0& 1
\end{bmatrix}
$$
Which is the case indeed. 

This is a very important property of basis transformations, and it is called **invertibility**. 

The transformation from one basis to another is invertible, and the inverse transformation is the transformation in the other direction.