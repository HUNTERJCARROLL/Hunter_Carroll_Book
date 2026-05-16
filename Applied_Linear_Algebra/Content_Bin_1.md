---
title: Chapter 1 - Notes
author: Hunter Carroll
---

# Vector Spaces

> <span style="color:#fa9f02">**Definition 1.19** *(Addition, Scalar Multiplication)*</span>
>
> - An *addition* on a set $V$ is a function that assigns an element $u+v \in V$ to each pair of elements $u, v \in V$.
> - A *scalar multiplication* on a set $V$ is a function that assigns an element $\lambda v \in V$ to each $\lambda \in F$ and each $v \in V$.

**<span style = 'color: #faee02'>Example.</span>** Let $V = \mathbb{R}^2$. If $u = (1,2)$ and $v = (3,4)$, then
$$
u + v = (1,2) + (3,4) = (4,6) \in V.
$$

**<span style = 'color: #faee02'>Example.</span>** Let $V = \mathbb{R}^2$ over $\mathbb{R}$. If $\lambda = 3$ and $v = (2,-1)$, then
$$
\lambda v = 3(2,-1) = (6,-3) \in V.
$$

The formal definition of a vector space follows.

---

> <span style="color:#fa9f02">**Definition 1.20** *(Vector Space)*</span>
>
> A *vector space* is a set $V$ along with an addition and scalar multiplication on $V$ such that the following properties hold:
>
> - **Commutativity** — $u + v = v + u$ for all $u, v \in V$
>
> - **Associativity** — $(u+v)+w = u+(v+w)$ and $(ab)v = a(bv)$  
>   for all $u, v, w \in V$ and $a, b \in F$
>
> - **Additive Identity** — there exists $0 \in V$ such that $v + 0 = v$ for all $v \in V$
>
> - **Additive Inverse** — for every $v \in V$, there exists $w \in V$ such that $v + w = 0$
>
> - **Multiplicative Identity** — $1v = v$ for all $v \in V$
>
> - **Distributive Properties** — $a(u+v) = au+av$ and $(a+b)v = av+bv$  
>   for all $a, b \in F$ and $u, v \in V$