---
title: Matrix formulation of basis change
template: default
---
Let us pick up the example in $\mathbb{R}^3$
The expansion of the old basis $\mathbf{e}_i$ in the new basis $\mathbf{f}_i$ was

$$
\begin{aligned}
(1,0,0)=0(1,1,1)+\frac{1}{2}(1,-1,1)+\frac{1}{2}(1,1,-1)\\
(0,1,0)=\frac{1}{2}(1,1,1)-\frac{1}{2}(1,-1,1)+0(1,1,-1)\\
(0,0,1)=\frac{1}{2}(1,1,1)+0(1,-1,1)-\frac{1}{2}(1,1,-1)
\end{aligned}
$$

<h3 class="h3-blue">Matrix formulation</h3>

We construct the coordinate change matrix by making the the expansion coefficients columns like

$$
\begin{bmatrix}
d_1 \\
d_2\\
d_3
\end{bmatrix}
=
\begin{bmatrix}
0           & \frac{1}{2} &\frac{1}{2} \\
\frac{1}{2} & -\frac{1}{2}& 0\\
\frac{1}{2} & 0           &-\frac{1}{2}
\end{bmatrix}
\,
\begin{bmatrix}
c_1 \\
c_2\\
c_3
\end{bmatrix}
$$

And using the matrix multiplication we obtain
$$
d_1=\frac{1}{2}(c_2+c_3),d_2=\frac{1}{2}(c_1-c_2), d_3=\frac{1}{2}(c_1-c_3)
$$
