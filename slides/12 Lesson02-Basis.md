---
title: Change of Basis
template: default
---

We have the known coordinates $c_j$

$$
v=\sum_{j=1}^n c_j\mathbf{e}_j
$$

But any of the basis vectors $\mathbf{e}_j$ can be expressed as a linear combination in the basis $\mathbf{f}_i$. That is

$$
\mathbf{e}_j=\sum_{i=1}^n a_{ij}\mathbf{f}_i
$$  

Which implies

$$
v=\sum_{j=1}^n c_j\mathbf{e}_j=\sum_{j=1}^n c_j \sum_{i=1}^n a_{ij}\mathbf{f}_i= \sum_{i=1}^n (\sum_{j=1}^n a_{ij}c_j)  \mathbf{f}_i=\sum_{i=1}^n d_i \mathbf{f}_i
$$

Where the i'th coordinate $d_i$ in the basis $\mathbf{f}_i$ is

$$
d_i= \sum_{j=1}^n a_{ij}c_j
$$


