---
title: Determinant
template: default
---

The matrix has an inverse if the determinant is non-zero

The determinant has a general formula

$$
\det (A) = \sum_{\sigma \in S_n} \operatorname{sgn} (\sigma)\, a_{1,\sigma (1)} a_{2,\sigma (2)} \cdots a_{n,\sigma (n)}
$$

where

$S_n$ is the set of all permutations of $\{ (1,2,\dots ,n)\}$

$sign (\sigma)$ is the sign of the permutation $+1$ or $-1$

This is a very unpractical formula but is can be calculated in other ways. But for now we will use **numpy** to
calculate it.

An intuitive understanding of the determinant is that the determinant gives the signed volume of the parallelepiped
spanned by the column vectors

