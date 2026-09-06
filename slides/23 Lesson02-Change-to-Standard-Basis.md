---
title: Change to standard basis
template: default
---


Change from $(1,1), (-1,1)$ to $(1,0)$ to $(0,1)$ then we have

$$
\begin{aligned}
(1,1)=1(1,0)+1(0,1)\\
(-1,1)=-1(1,0)+1(0,1)
\end{aligned}
$$

And as we discussed before the new coordinates $(d_1,d_2)$ are calculated by the old coordinates by

$$
\begin{aligned}
d_1&=1c_1+ -1c_2=c_1-c_2\\
d_2&=1c_1+ 1c_2=c_1+c_2
\end{aligned}
$$

Or put in matrix form

$$
\begin{bmatrix}
d_1 \\
d_2
\end{bmatrix}
=
\begin{bmatrix}
1 & -1 \\
1 & 1
\end{bmatrix}
\,
\begin{bmatrix}
c_1 \\
c_2
\end{bmatrix}
$$

which implies new coefficients are
$$
\begin{aligned}
d_1=c_1-c_2,d_2=c_1+c_2
\end{aligned}
$$
