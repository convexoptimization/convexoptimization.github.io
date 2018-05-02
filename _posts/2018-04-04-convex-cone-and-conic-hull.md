---
layout: post
title: "Convex cone and conic hull"
categories: [Convex theory]
maths: true
featured-img: convex-cone.jpg
---
# Cone and convex cone

A set $C\subseteq\mathbb R^n$ is called a **cone** if for every $x\in C$ and $\lambda\geqslant 0$ we have $\lambda x\in C$.

A set $C$ is called a **convex cone** if $C$ is a cone and $C$ is convex, i.e. for any $x_1,x_2\in C$ and
$\lambda_1, \lambda_2 \geqslant0$ we have

$$
\lambda_1x_1 +\lambda_2x_2\in C.
$$

# Conic combination

A **conic combination** of the points $x_1,\ldots, x_n$ is a point of form $\lambda_1x_1+\ldots+\lambda_nx_n$ with $\lambda_i\geqslant0\ \ \forall i=1,\ldots,n$.

The following table shows the difference between affine combination, convex combination and conic combination

|  Affine combination  |  Convex combination  |  Conic combination  |
| :------------------ | :------------------ | :----------------- |
| Form: $\ \lambda_1x_1 +\ldots+ \lambda_nx_n$ | Form: $\ \lambda_1x_1 +\ldots+ \lambda_nx_n$ | Form: $\ \lambda_1x_1 +\ldots+ \lambda_nx_n$ | 
| Where $\ \lambda_i\in\mathbb R$ and $\sum_{i=1}^n \lambda_i=1$ | Where $\ \lambda_i\geqslant0 $ and $\sum_{i=1}^n \lambda_i=1$| Where $\ \lambda_i\geqslant0$|




# Conic hull

The set of all conic combination of points in $C$ is called the **conic hull** of $C$

$$
\text{cone}(C) = \left\{ \sum_{i=1}^n \lambda_i x_i\ \Big|\ \ x_i\in C \text{ and } \lambda_i\geqslant 0 \ \ \forall i=1,\ldots,n\right\}.
$$

<div class="alert tip" markdown="1">
**Tip:** In the definition of conic hull, we only need $\lambda_i\geqslant0$
</div>
