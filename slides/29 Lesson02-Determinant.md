---
title: Determinant and linear independence
template: default
---

A very relevant use of the determinant is when we want to examine a set of vectors for linear independence. 

We will exemplify in $\mathbb{R}^3$, but the technique generalized immediately.


Consider the set of vectors under test for linear independence
$$
\begin{aligned}
\mathbf{b}_1&= (1,-1,1)\\
\mathbf{b}_2&= (1,1,0)\\
\mathbf{b}_3&= (1,-1,-1)
\end{aligned}
$$

The condition for linear independence is stated by

$$
c_1\mathbf{b}_1+c_2\mathbf{b}_2+c_3\mathbf{b}_3=\mathbf{0}\Rightarrow c_1=c_2=c_3=0
$$

This is equivalently stated in matrix formulation as
$$
\begin{bmatrix}
1 & 1& 1\\
-1& 1& -1\\
1 & 0& -1
\end{bmatrix}
\,
\begin{bmatrix}
c_1\\
c_2\\
c_3
\end{bmatrix}
=
\begin{bmatrix}
0\\
0\\
0
\end{bmatrix}
$$

And if we are to be sure that the only solution is $c_1=c_2=c_3=0$ the matrix has to be invertible. 
And then the determinant must be non-zero

