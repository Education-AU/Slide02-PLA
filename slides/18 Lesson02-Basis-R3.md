---
title: Change of Basis R³
template: default
---

$$
\begin{aligned}
1 &= a_{11}+a_{21}+a_{31} &\qquad 0 &= a_{12}+a_{22}+a_{32} &\qquad 0 &= a_{13}+a_{23}+a_{33}\\
0 &= a_{11}-a_{21}+a_{31} &\qquad 1 &= a_{12}-a_{22}+a_{32} &\qquad 0 &= a_{13}-a_{23}+a_{33}\\
0 &= a_{11}+a_{21}-a_{31} &\qquad 0 &= a_{12}+a_{22}-a_{32} &\qquad 1 &= a_{13}+a_{23}-a_{33}
\end{aligned}
$$

Which can be solved to
$$
\begin{aligned}
a_{11}=0,a_{21}=\frac{1}{2},a_{31}=\frac{1}{2}\\
a_{12}=\frac{1}{2},a_{22}=-\frac{1}{2},a_{32}=0\\
a_{13}=\frac{1}{2},a_{23}=0,a_{33}=-\frac{1}{2}
\end{aligned}
$$
That is

$$
\begin{aligned}
(1,0,0)=0(1,1,1)+\frac{1}{2}(1,-1,1)+\frac{1}{2}(1,1,-1)\\
(0,1,0)=\frac{1}{2}(1,1,1)-\frac{1}{2}(1,-1,1)+0(1,1,-1)\\
(0,0,1)=\frac{1}{2}(1,1,1)+0(1,-1,1)-\frac{1}{2}(1,1,-1)
\end{aligned}
$$
