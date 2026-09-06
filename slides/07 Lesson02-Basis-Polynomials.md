---
title: Vector Space of Polynomials basis
template: default
---

Let $\mathbb{P}$ be the **vector space** of all real polynomials of one variable.

That this is a vector space is easy to check.

Then the claim is that the set $B=\{t^0,t^1,t^2,t^3,t^4\dots \}$ is a basis

First notice that the set $B$ is **not finite**.


<h3 class="h3-blue">B is linear independent</h3>
Pick any finite set say $\{ t^{k_1},t^{k_2} \dots t^{k_n} \}$
where $k_i\neq k_{j}$ for $i\neq j$
Consider
$$
c_1t^{k_1}+c_2t^{k_2}+ \dots +c_nt^{k_n} =0
$$
Since a polynomial of finite degree can at most have finite many zeroes all coefficients must be zero.

<h3 class="h3-blue">$\mathbb{P}=\textbf{Span}(\textbf{B})$</h3>
To prove this fact, pick any $v\in \mathbb{P}$. By definition a polynomial is finite in degree. And therefore is a
linear combination of $n$ of the basis elements



