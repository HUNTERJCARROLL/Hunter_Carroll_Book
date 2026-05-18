---
title: Vector Spaces
author: Hunter Carroll
description: Introductory notes on vector spaces, scalar multiplication, and examples over real and complex fields.
---

# Vector Spaces

:::{admonition} Definition 1.19: Addition and Scalar Multiplication
:class: note

An **addition** on a set $V$ is a function that assigns an element

$$
u + v \in V
$$

to each pair of elements $u, v \in V$.

A **scalar multiplication** on a set $V$ is a function that assigns an element

$$
\lambda v \in V
$$

to each scalar $\lambda \in F$ and each vector $v \in V$.
:::

:::{admonition} Example: Addition in $\mathbb{R}^2$
:class: tip

Let $V = \mathbb{R}^2$. If

$$
u = (1,2), \qquad v = (3,4),
$$

then

$$
u + v = (1,2) + (3,4) = (4,6) \in V.
$$

So addition combines vectors component by component.
:::

:::{admonition} Example: Scalar Multiplication in $\mathbb{R}^2$
:class: tip

Let $V = \mathbb{R}^2$ over $\mathbb{R}$. If

$$
\lambda = 3, \qquad v = (2,-1),
$$

then

$$
\lambda v = 3(2,-1) = (6,-3) \in V.
$$

So scalar multiplication stretches, shrinks, or reverses the direction of a vector depending on the scalar.
:::

The formal definition of a vector space follows.

---

:::{admonition} Definition 1.20: Vector Space
:class: important

A **vector space** over a field $F$ is a set $V$ together with an addition operation and a scalar multiplication operation satisfying the following properties.

For all $u,v,w \in V$ and all $a,b \in F$:

1. **Commutativity**

   $$
   u + v = v + u.
   $$

2. **Associativity of Addition**

   $$
   (u+v)+w = u+(v+w).
   $$

3. **Associativity of Scalar Multiplication**

   $$
   (ab)v = a(bv).
   $$

4. **Additive Identity**

   There exists an element $0 \in V$ such that

   $$
   v + 0 = v.
   $$

5. **Additive Inverse**

   For every $v \in V$, there exists $w \in V$ such that

   $$
   v + w = 0.
   $$

6. **Multiplicative Identity**

   $$
   1v = v.
   $$

7. **Distributivity over Vector Addition**

   $$
   a(u+v) = au + av.
   $$

8. **Distributivity over Scalar Addition**

   $$
   (a+b)v = av + bv.
   $$
:::

## The Role of the Field $F$

It is important to be precise about the field $F$ because scalar multiplication depends on the choice of scalars.

For example:

- $\mathbb{R}^n$ is a vector space over $\mathbb{R}$.
- $\mathbb{C}^n$ is a vector space over $\mathbb{C}$.

A vector space over $\mathbb{R}$ is called a **real vector space**, while a vector space over $\mathbb{C}$ is called a **complex vector space**.

:::{note}
The simplest vector space is $\{0\}$, the set containing only the zero vector.

It satisfies all the vector space axioms:

$$
0 + 0 = 0,
$$

and for every scalar $\lambda \in F$,

$$
\lambda 0 = 0.
$$
:::

:::{note}
The space $F^\infty$ is the set of all infinite sequences whose entries come from the field $F$.

An element of $F^\infty$ has the form

$$
(a_1,a_2,a_3,\dots),
$$

where each $a_i \in F$.

This is a vector space because infinite sequences can be added and scalar multiplied component by component. The main difference between $F^n$ and $F^\infty$ is that $F^n$ has finitely many coordinates, while $F^\infty$ has infinitely many.
:::

## Function Spaces

:::{admonition} Example: A Vector Space of Functions
:class: tip

Let $S$ be a set. Then $F^S$ denotes the set of all functions from $S$ to $F$:

$$
F^S = \{f : S \to F\}.
$$

For $f,g \in F^S$, define addition by

$$
(f+g)(x) = f(x) + g(x), \qquad \forall x \in S.
$$

For $\lambda \in F$ and $f \in F^S$, define scalar multiplication by

$$
(\lambda f)(x) = \lambda f(x), \qquad \forall x \in S.
$$

With these operations, $F^S$ is a vector space over $F$.
:::

:::{admonition} Key Idea
:class: important

A vector space is not just a set. It is a set equipped with two compatible operations:

1. vector addition  
2. scalar multiplication  

The axioms guarantee that vectors can be combined algebraically in a consistent way.
:::