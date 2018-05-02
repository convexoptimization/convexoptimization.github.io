---
layout: post
title: "Convex cone and conic hull"
categories: [Convex theory]
maths: true
featured-img: convex-cone.jpg
---
# Affine sets

A set $C\subseteq\mathbb R^n$ is **affine** if the line through any two points in $C$ lies in $C$. Namely, for any $x_1, x_2\in C$ and $\lambda\in\mathbb R$, we have $\lambda x_1+(1-\lambda)x_2\in C$

If $C$ is an affine set then $C$ can be expressed as

$$
C = x_0 + V=\{x_0+v|\ v\in V\}, 
$$ 

where $x_0$ is a point in $C$ and $V$ is a subspace. It means that for any affine set $C$, there is a subspace associated with $C$. We define the *dimension* of $C$ as the simension of the subspace $V$.

Given a set $C$ and $x_1,\ldots,x_n\in C$, we refer to a point of form $\lambda_1x_1  + \ldots + \lambda_n x_n$, where $\lambda_1+\ldots + \lambda_n=1$, as an *affine combination* of the points $x_1,\ldots,x_n$.

The set of all affine combinations of points in $C$ is called the **affine hull** of $C$, i.e.

$$
\text{aff}(C) = \left\{ \sum_{i=1}^n \lambda_i x_i\ \Big|\ \ x_i\in C, \lambda_i\in\mathbb R \text{ and} \sum_{i=1}^n\lambda_i=1 \right\}.
$$

**Note:** The affine hull of $C$ is the smallest affine set that contains $C$.

# Convex sets

A set $C$ is **convex** if the line segment between any two points in $C$ lies in $C$. Namely, for any $x_1, x_2\in C$ and $\lambda\in\mathbb [0,1]$ we have $\lambda x_1+(1-\lambda)x_2\in C$
<div class="alert note" markdown="1">
**Note:** Different from the definition of affine sets, in a convex set we only need the **segment** lies on it, which characterized by the range of $\lambda$
</div>

Roughly speaking, in a convex set, any point can be seen by each other through an straight path between them.
Every affine set is also convex.

Given a set $C$ and $x_1,\ldots,x_n\in C$, we call to a point of form $\lambda_1x_1  + \ldots + \lambda_n x_n$, where $\lambda_i\geqslant0$ and $\lambda_1+\ldots + \lambda_n=1$, a *convex combination* of the points $x_1,\ldots,x_n$.

The set of all convex combination of points in $C$ is called the **convex hull** of $C$

$$
\text{conv}(C) = \left\{ \sum_{i=1}^n \lambda_i x_i\ \Big|\ \ x_i\in C, \lambda_i\geqslant 0 \text{ and} \sum_{i=1}^n\lambda_i=1 \right\}.
$$

<div class="alert note" markdown="1">
**Note:** In the definition of affine hull, $\lambda_i\in\mathbb R$, while in the definition of convex hull, $\lambda_i\geqslant0$
</div>
