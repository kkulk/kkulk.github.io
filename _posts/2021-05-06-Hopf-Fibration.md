---
layout: post
title: The Hopf Fibration
---

$$  \def\acts{\curvearrowright}$$

### This post is based on John Lee's "Introduction to Smooth Manifolds" and lectures by Prof. Richard Bamler at UC Berkeley. 

The action of the circle $$\mathbb{S}^1$$ on the higher dimensional sphere $$\mathbb{S}^{2n+1}$$ is one of the most profound objects in differential geometry. We study the consequences of this action here.

First, we note that the manifold $$\mathbb{S}^{2n+1} \subset \mathbb{R}^{2n+2} \subset \mathbb{C}^{n+1}$$ consists of elements of the form: 

$$\begin{align} \{(z_1, \dots, z_{n+1} ) \in \mathbb{C}^{n+1} | |z_1|^2 + \dots + |z_{n+1}|^2 = 1\} \end{align}$$

The circle $$\mathbb{S}^1$$ acts on the sphere in the following way. We have that $$\mathbb{S}^1 \acts \mathbb{S}^{2n+1}$$ as: 

$$ \begin{align}
\lambda \cdot (z_1, \dots, z_{n+1}) = (\lambda z_1, \dots, \lambda z_n)
\end{align} $$

The orbits of this action are $$ \{ ( \lambda z_1, \dots, \lambda z_{n+1}) : \lambda \in S^1 \} $$ for any $$(z_1, \dots, z_{n+1} ) \in \mathbb{S}^{2n+1}$$ and the orbit space is: 

$$\begin{align}
\mathbb{S}^1 \ \mathbb{S}^{2n+1} = \{ [z_1 , \dots, z_n ] \} = \mathbb{C} P^n
\end{align}$$

This is remarkable! The action of the circle on the $$2n+1$$-dimensional sphere splits the sphere into complex projective spaces of $$n$$-dimension. Further, we can check that the map: 

$$\begin{align}
\pi: \mathbb{S}^{2n+1} \rightarrow \mathbb{C} P^n \\ 
\pi(z_1, \dots, z_{n+1})  = [z_1, \dots, z_{n+1} ]
\end{align}$$
is a submersion. 
