---
title: Chapter 1 - Notes
author: Hunter Carroll
---

# Vector Spaces

> <span style="color:#e8a020">**Definition 1.19** *(Addition, Scalar Multiplication)*</span>
>
> - An *addition* on a set $V$ is a function that assigns an element $u+v \in V$ to each pair of elements $u, v \in V$.
> - A *scalar multiplication* on a set $V$ is a function that assigns an element $\lambda v \in V$ to each $\lambda \in F$ and each $v \in V$.

<span style="color:#5ab4e8">**Example.**</span> Let $V = \mathbb{R}^2$. If $u = (1,2)$ and $v = (3,4)$, then
$$
u + v = (1,2) + (3,4) = (4,6) \in V.
$$

<span style="color:#5ab4e8">**Example.**</span> Let $V = \mathbb{R}^2$ over $\mathbb{R}$. If $\lambda = 3$ and $v = (2,-1)$, then
$$
\lambda v = 3(2,-1) = (6,-3) \in V.
$$

The formal definition of a vector space follows.

---

> <span style="color:#e8a020">**Definition 1.20** *(Vector Space)*</span>
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

However, we need to be precise in how we define $F$ as scalar multiplication in a vector space depends on $F$. For example, we could say "$\mathbb{R}^n$ is a vector space over $\mathbb{R}$" or "$\mathbb{C}^n$ is a vector space over $\mathbb{C}$". That is, a vector space over $\mathbb{R}$ is a real vector space and a vector space over $\mathbb{C}$ is a complex vector space.

<span style="color:#7ec87e">**Note.**</span> The simplest vector space is $\{0\}$ containing only a single point. It still qualifies as a vector space because it satisfies all the vector space rules: adding zero to zero gives zero, multiplying zero by any scalar gives zero, etc.

<span style="color:#7ec87e">**Note.**</span> The example given in the text is $F^{\infty}$, which is the set of all infinite sequences whose entries come from the field $F$, is conveying that $F^{\infty}$ is a vector space because infinite sequences can be added or scalar multiplied component by component. The only difference is that $F^{n}$ has finitely many coordinates.

<span style="color:#5ab4e8">**Example. (A vector space involving a set of functions)**</span>  

* If $S$ is a set, then $F^S$ denotes the set of functions from $S$ to $F$. 

* For $f, g \in F^S$, the sum $f+g \in F^S$ is the function defined by, 

$$
(f+g)(x)  = f(x) + g(x), \qquad \forall x \in S
$$

* For $\lambda \in F$ and $f \in F^S$ the product $\lambda f \in F^S$ is the function defined by, 

$$
(\lambda f)(x) = \lambda f(x),  \qquad \forall x \in S
$$