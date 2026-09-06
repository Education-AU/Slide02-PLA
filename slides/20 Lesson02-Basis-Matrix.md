---
title: Matrix formulation of basis change
template: default
---
This general calculational procedure can be organized into a special scheme which involves **matrices**. 

Matrices are simply data organized in two-dimensional arrays. 

If we organize the coefficients $aij$ into a table and the coordinates into a column
$$
\begin{bmatrix}
d_{1}\\
d_{2}\\
\vdots\\
d_n
\end{bmatrix}
=
\begin{bmatrix}
a_{11}& a_{12}&\dots& a_{1n}\\
a_{21}& a_{22}&\dots& a_{2n}\\
\vdots & \vdots& \ddots& \vdots \\
a_{n1}& a_{n2}&\dots& a_{nn}
\end{bmatrix}
\begin{bmatrix}
c_{1}\\
c_{2}\\
\vdots\\
c_n
\end{bmatrix}
$$

And we introduce a special operation called matrix multiplication we will see that this replicates the previous calculation

First of all we observe that the columns in the matrix are the coordinates of the initial basis in the target basis. $a_{1k},a_{2k},\dots,a_{nk}$ are the coordinates of $\mathbf{e}_k$ in the target basis $\mathbf{f}_i$

The way to conduct this operation in accordance with the sum formula is easiest shown by hand
